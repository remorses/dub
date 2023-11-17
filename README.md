## Introduction

some content

xxxxx is an open-source link management tool for modern marketing teams to create, share, and track short links. Built with [Vercel Edge Functions](http://vercel.com/edge), [Upstash Redis](https://docs.upstash.com/redis), and [PlanetScale MySQL](https://planetscale.com/).

Here are some of the features that wow so cool  Dub provides out-of-the-box:

- [Built-in Analytics](#built-in-analytics)
- [Custom Domains](#custom-domains)
- [QR Code Generator](#qr-code-generator)
- [OG Image Proxy](#og-image-proxy)

### Built-in Analytics

[sdf](sdf)

some more stuff in here loool

🎉 Welcome to Dub, the ultimate link analytics dashboard that will blow your mind! 🚀📊

Picture this: You've just created an amazing link that you want to share with the world. But wait, wouldn't it be awesome to know more about who's clicking on it? 🤔 That's where Dub comes in, and boy, does it pack a punch! 💥

Dub is not your ordinary link analytics tool, oh no! It's like a supercharged detective that can tell you everything you need to know about the people clicking on your links. 🕵️‍♀️🔍 From their location 🌍 to the device they're using 📱, and even the browser they prefer to surf the web with 🌐, Dub has got you covered.

Imagine this: You've just shared your link on social media, and within seconds, Dub starts collecting data like a boss. 📈💪 It's like having a personal army of tiny, intelligent robots that gather all the juicy information for you. 🤖💼

And here's the best part: Dub presents all this information to you in a visually stunning, easy-to-understand dashboard. 📈📊 It's like a party for your eyes, with graphs and charts dancing around, showing you the insights you crave. 🎉💃

But wait, there's more! Dub doesn't just stop at giving you the cold, hard stats. It also adds a touch of humor to your data. 🤣 Imagine seeing a little emoji pop up when someone from a faraway land clicks on your link. 🌍🔍🌟 It's like your link is going on a world tour, spreading joy and laughter. 😄✈️

And don't worry, we've got plenty of emojis to sprinkle throughout the dashboard. 🌈🎉 From smiley faces to thumbs up, your analytics experience will be a rollercoaster of emotions. 😂👍

So why settle for boring link analytics when you can have the Dub experience? Join the party now and let your links become the life of the party! 🎊🥳💃

### Custom Domains

You can easily configure custom domains on Dub – just add an A/CNAME record to your DNS provider and you're good to go. This is built on the [Vercel Domains API](https://domains-api.vercel.app/).

### QR Code Generator

You can easily generate and customize QR codes for your links, which can be used for flyers, posters, powerpoint presentations, etc.

### OG Image Proxy

Add a custom OG image in front of your target URL. Bots like Twitter/Facebook will be served this image, while users will be redirected to your target URL.

## Deploy Your Own

> Note: one-click deployment is a bit broken at the moment – you'll need to change some of the hard-coded values in the codebase to get it working. We're working on fixing this.

You can deploy your own hosted version of Dub for greater privacy & control. Just click the link below to deploy a ready-to-go version of Dub to Vercel.

very nice indeed

wow so cool

## Tech Stack

- [Next.js](https://nextjs.org/) – framework
- [Typescript](https://www.typescriptlang.org/) – language
- [Tailwind](https://tailwindcss.com/) – CSS
- [Upstash](https://upstash.com/) – redis
- [Tinybird](https://tinybird.com/) – analytics
- [PlanetScale](https://planetscale.com/) – database
- [NextAuth.js](https://next-auth.js.org/) – auth
- [Vercel](https://vercel.com/) – hosting
- [Stripe](https://stripe.com/) – payments

## Implementation

Dub is built as a standard Next.js application with [Middleware](https://nextjs.org/docs/advanced-features/middleware) to handle multi-tenancy, inspired by [the Vercel Platforms Starter Kit](https://github.com/vercel/platforms).

[Redis](https://redis.io/) is used as the caching layer for all short links.

[Clickhouse](https://clickhouse.com/) ([Tinybird](https://tinybird.com/)) is used as the analytics database for storing link click data.

[MySQL](https://www.mysql.com/) is used as the database for storing user data, project data, and link metadata. You can refer to the Prisma schema [here](/prisma/schema.prisma).

## Contributing

We love our contributors! Here's how you can contribute:

- [Open an issue](https://github.com/steven-tey/dub/issues) if you believe you've encountered a bug.
- Make a [pull request](https://github.com/steven-tey/dub/pull) to add new features/make quality-of-life improvements/fix bugs.

## Author

- Steven Tey ([@steventey](https://twitter.com/steventey))

## License

Inspired by [Plausible](https://plausible.io/), Dub is open-source under the GNU Affero General Public License Version 3 (AGPLv3) or any later version. You can [find it here](https://github.com/steven-tey/dub/blob/main/LICENSE.md).

xxx