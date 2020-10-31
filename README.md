# 💖 Frens

![lint status](https://github.com/rishiosaur/frens/workflows/lint/badge.svg)
![format status](https://github.com/rishiosaur/frens/workflows/format/badge.svg)
![GitHub](https://img.shields.io/github/license/rishiosaur/frens)
![GitHub issues](https://img.shields.io/github/issues/rishiosaur/frens)
![GitHub contributors](https://img.shields.io/github/contributors/rishiosaur/frens)
![GitHub last commit](https://img.shields.io/github/last-commit/rishiosaur/frens)

A minimal link shortener powered by Next.js and Vercel.

## Structure of a route:

```
{
  url: string
  name: string
  public: boolean
  title?: string
  description?: string
}
```

`url` is the end URL that you'd like to redirect to.
`name` is the name of the route that redirects to `url`.
`public` is a boolean that determines whether or not this redirect shows up in the public directory.

## Adding yourself

The websites that show up on [the website](https://w.rishi.cx) can be found over at [`routes.json`](https://github.com/rishiosaur/frens/blob/main/routes.json)!

Just add yourself to the array in an object that conforms to the above protocol!

_Note_: You _must_ be on the Hack Club Slack (and be an active member) to be accepted into the collection :p
