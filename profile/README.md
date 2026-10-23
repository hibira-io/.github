<p align="center">
  <a href="https://hikibi.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.png">
      <img src="assets/wordmark.png" alt="Hikibi 響" width="320">
    </picture>
  </a>
</p>

<p align="center"><b>Realtime WebSockets and push notifications, built for Asia-Pacific.</b></p>

<p align="center">
  <a href="https://status.hikibi.io"><img alt="Service status" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fstatus.hikibi.io%2Fapi%2Fstatus&query=%24.status&label=status&color=informational&cacheSeconds=300"></a>
  <a href="https://hikibi.io"><img alt="hikibi.io" src="https://img.shields.io/website?url=https%3A%2F%2Fhikibi.io&label=hikibi.io"></a>
  <a href="https://hikibi.io/pricing"><img alt="Free plan" src="https://img.shields.io/badge/free%20plan-no%20credit%20card-111110"></a>
</p>

<p align="center">
  <a href="https://hikibi.io">Website</a> ·
  <a href="https://hikibi.io/guides">Guides</a> ·
  <a href="https://hikibi.io/migrate">Migrate</a> ·
  <a href="https://hikibi.io/pricing">Pricing</a> ·
  <a href="https://status.hikibi.io">Status</a>
</p>

---

## 👋 Hi, we're Hikibi 響

**響** means "echo" or "resonance": a message sent once and heard
everywhere at the same moment. That is what we build.

Hikibi is a hosted realtime service run from Asia-Pacific. Your backend
publishes an event over a simple HTTP API and Hikibi delivers it instantly to
every browser and app that is listening, whether that is one user or tens of
thousands. We keep the WebSocket connections open, scale them, and track who
is online, so you don't have to run realtime servers yourself.

Too often, apps used in Taipei, Tokyo, Seoul, Hong Kong and Singapore send
their realtime traffic halfway around the world and back. We think realtime infrastructure for Asia should run in Asia, speak its
customers' languages, and be priced so that growing an audience never turns
into a surprise bill.

## ✨ What you get

- **Drop-in Pusher compatibility.** Hikibi speaks the Pusher Channels
  protocol 7 and HTTP API. Laravel Broadcasting, Laravel Echo, `pusher-js`
  and the Pusher server SDKs work unchanged: you only change the host and keys.
- **Low latency across Asia.** Hosted in Hong Kong, a short hop from Taipei,
  Tokyo, Seoul and Singapore.
- **Pricing that doesn't punish fan-out.** Only the events you publish count.
  Delivering one event to ten thousand subscribers costs the same as
  delivering it to one, and we never bill overages.
- **Presence, private and encrypted channels.** Who-is-online lists that stay
  correct across nodes, plus client events for typing indicators and cursors.
- **Push notifications.** Send to iOS, Android and browsers through a
  Beams-compatible API, included in every plan at no extra cost.
- **Webhooks and live usage.** Signed webhooks for channel and presence
  events, and a dashboard with live connections and today's messages per app.
- **Works with AI agents.** Claude Code, Cursor and other MCP clients can
  create apps, read usage and wire up an SDK through our MCP server at
  `https://hikibi.io/mcp`.
- **In your language.** Dashboard, emails, checkout and support in English,
  繁體中文, 简体中文, 日本語 and 한국어.

## 🚀 Get started in three steps

1. **Create an app** at [hikibi.io](https://hikibi.io) to get its ID, key and secret.
2. **Update your settings**: set the host and credentials in your server SDK
   and in Echo or `pusher-js`.
3. **Deploy**: broadcast as before and watch connections and messages live in
   your dashboard.

Moving from another provider? The [migration guide](https://hikibi.io/migrate)
lists every setting to change.

## 🧩 Works with your stack

<p>
  <img height="28" alt="JavaScript" title="JavaScript" src="https://raw.githubusercontent.com/github/explore/main/topics/javascript/javascript.png">
  <img height="28" alt="TypeScript" title="TypeScript" src="https://raw.githubusercontent.com/github/explore/main/topics/typescript/typescript.png">
  <img height="28" alt="Node.js" title="Node.js" src="https://raw.githubusercontent.com/github/explore/main/topics/nodejs/nodejs.png">
  <img height="28" alt="PHP" title="PHP" src="https://raw.githubusercontent.com/github/explore/main/topics/php/php.png">
  <img height="28" alt="Laravel" title="Laravel" src="https://raw.githubusercontent.com/github/explore/main/topics/laravel/laravel.png">
  <img height="28" alt="Python" title="Python" src="https://raw.githubusercontent.com/github/explore/main/topics/python/python.png">
  <img height="28" alt="Go" title="Go" src="https://raw.githubusercontent.com/github/explore/main/topics/go/go.png">
  <img height="28" alt="Ruby" title="Ruby" src="https://raw.githubusercontent.com/github/explore/main/topics/ruby/ruby.png">
  <img height="28" alt="Java" title="Java" src="https://raw.githubusercontent.com/github/explore/main/topics/java/java.png">
  <img height="28" alt=".NET" title=".NET" src="https://raw.githubusercontent.com/github/explore/main/topics/dotnet/dotnet.png">
  <img height="28" alt="Swift" title="Swift" src="https://raw.githubusercontent.com/github/explore/main/topics/swift/swift.png">
  <img height="28" alt="Kotlin" title="Kotlin" src="https://raw.githubusercontent.com/github/explore/main/topics/kotlin/kotlin.png">
  <img height="28" alt="Flutter" title="Flutter" src="https://raw.githubusercontent.com/github/explore/main/topics/flutter/flutter.png">
</p>

Step-by-step [integration guides](https://hikibi.io/guides) cover JavaScript,
Laravel, PHP, Node.js, Python, Go, Ruby, Java, .NET, iOS, Android and Flutter.

## 📦 Our open-source SDKs

| Repository | Platform | Install |
|---|---|---|
| [large-presence-js](https://github.com/hikibi-io/large-presence-js) | Browsers, `@hikibi/large-presence`: rooms of up to 100,000 members with pusher-js or Laravel Echo | npm |
| [hikibi-push-web](https://github.com/hikibi-io/hikibi-push-web) | Browsers, `@hikibi/push-web`: web push notifications | npm or jsDelivr |
| [hikibi-push-android](https://github.com/hikibi-io/hikibi-push-android) | Android (Kotlin/Java), package `io.hikibi.push` | JitPack |
| [hikibi-push-ios](https://github.com/hikibi-io/hikibi-push-ios) | iOS (Swift), module `HikibiPush` | Swift Package Manager |

For public, private and presence channels, keep the Pusher-compatible client you already use and
point it at Hikibi.

## 💰 Simple plans

Start free with 100 peak connections and 200,000 messages a day, no credit
card required. Paid plans run from US$29 to US$599 a month for up to 30,000
peak connections, with every feature in every plan. Enterprise plans come with
a 99.9% uptime SLA. See [pricing](https://hikibi.io/pricing).

## 💬 Talk to us

- 📖 Docs: [hikibi.io/guides](https://hikibi.io/guides)
- 🟢 Status: [status.hikibi.io](https://status.hikibi.io)
- 🐛 SDK bugs: open an issue in the SDK's repository
- 📫 Support: **support@hikibi.io**
- 🤝 Sales and Enterprise: **sales@hikibi.io** or [contact sales](https://hikibi.io/contact-sales)
- 🔒 Security: **security@hikibi.io** (please don't open a public issue)

---

<sub>Pusher, Pusher Channels and Pusher Beams are trademarks of their
respective owner. Hikibi is an independent service and is not affiliated
with, endorsed by or sponsored by Pusher or its owner. "Pusher-compatible" and
"Beams-compatible" describe protocol and API compatibility only.</sub>
