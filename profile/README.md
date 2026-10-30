<p align="center">
  <a href="https://hibira.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.png">
      <img src="assets/wordmark.png" alt="Hibira" width="320">
    </picture>
  </a>
</p>

<p align="center"><b>Every Event. Every Connection.</b><br>Realtime communication infrastructure: WebSockets and push notifications, built for Asia-Pacific.</p>

<p align="center">
  <a href="https://status.hibira.io"><img alt="Service status" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fstatus.hibira.io%2Fapi%2Fstatus&query=%24.status&label=status&color=informational&cacheSeconds=300"></a>
  <a href="https://hibira.io"><img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fhibira.io&label=website"></a>
  <a href="https://hibira.io/pricing"><img alt="Free plan" src="https://img.shields.io/badge/free%20plan-no%20credit%20card-111110"></a>
</p>

<p align="center">
  <a href="https://hibira.io">Website</a> ·
  <a href="https://hibira.io/guides">Guides</a> ·
  <a href="https://hibira.io/migrate">Migrate</a> ·
  <a href="https://hibira.io/pricing">Pricing</a> ·
  <a href="https://status.hibira.io">Status</a>
</p>

---

## 👋 Hi, we're Hibira

**Every Event. Every Connection.** Hibira is realtime communication
infrastructure: one event sent, and every connected user hears it at the
same moment.

Hibira (formerly Hikibi) is a hosted realtime service run from Asia-Pacific. Your backend
publishes an event over a simple HTTP API and Hibira delivers it instantly to
every browser and app that is listening, whether that is one user or tens of
thousands. We keep the WebSocket connections open, scale them, and track who
is online, so you don't have to run realtime servers yourself.

Too often, apps used in Taipei, Tokyo, Seoul, Hong Kong and Singapore send
their realtime traffic halfway around the world and back. We think realtime infrastructure for Asia should run in Asia, speak its
customers' languages, and be priced so that growing an audience never turns
into a surprise bill.

## ✨ What you get

- **Drop-in Pusher compatibility.** Hibira speaks the Pusher Channels
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
  events, and a dashboard with each app's connections and messages, live
  from the Starter plan up.
- **Works with AI agents.** Claude Code, Cursor and other MCP clients can
  create apps, read usage and wire up an SDK through our MCP server at
  `https://hibira.io/mcp`.
- **In your language.** Site, dashboard, emails and checkout in English,
  繁體中文, 简体中文, 日本語, 한국어, ไทย and Tiếng Việt; support in English,
  Chinese, Japanese and Korean.

## 🚀 Get started in three steps

1. **Create an app** at [hibira.io](https://hibira.io) to get its ID, key and secret.
2. **Update your settings**: set the host and credentials in your server SDK
   and in Echo or `pusher-js`.
3. **Deploy**: broadcast as before and watch connections and messages live in
   your dashboard.

Moving from another provider? The [migration guide](https://hibira.io/migrate)
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

Step-by-step [integration guides](https://hibira.io/guides) cover JavaScript,
Laravel, PHP, Node.js, Python, Go, Ruby, Java, .NET, iOS, Android and Flutter,
plus our own packages for React, Vue, Nuxt, Rails, Filament, Godot, Unity, n8n
and Terraform.

## 📦 Our open-source SDKs

| Repository | Platform | Install |
|---|---|---|
| [large-presence-js](https://github.com/hibira-io/large-presence-js) | Browsers, `@hibira-io/large-presence`: rooms of up to 100,000 members with pusher-js or Laravel Echo | npm |
| [hibira-push-web](https://github.com/hibira-io/hibira-push-web) | Browsers, `@hibira-io/push-web`: web push notifications | npm or jsDelivr |
| [hibira-push-android](https://github.com/hibira-io/hibira-push-android) | Android (Kotlin/Java), package `io.hibira.push` | JitPack |
| [hibira-push-ios](https://github.com/hibira-io/hibira-push-ios) | iOS and macOS (Swift), module `HibiraPush` | Swift Package Manager |

## 🔌 Packages and plugins

| Repository | Platform | Install |
|---|---|---|
| [react](https://github.com/hibira-io/react) | React 17–19, `@hibira-io/react`: hooks for events, presence and LLM streaming | npm |
| [vue](https://github.com/hibira-io/vue) | Vue 3 and 2.7, `@hibira-io/vue`: composables for events, presence and LLM streaming | npm |
| [nuxt](https://github.com/hibira-io/nuxt) | Nuxt 4, 3 and 2, `@hibira-io/nuxt`: module with server helpers | npm |
| [lobby-js](https://github.com/hibira-io/lobby-js) | Browsers, `@hibira-io/lobby`: game rooms with seats, a host and chat | npm |
| [spaces-js](https://github.com/hibira-io/spaces-js) | Browsers, `@hibira-io/spaces`: live cursors, avatars and locations | npm |
| [laravel](https://github.com/hibira-io/laravel) | Laravel, `hibira-io/laravel`: broadcasting, push notifications and webhooks | Composer |
| [filament](https://github.com/hibira-io/filament) | Filament 3–5, `hibira-io/filament`: live notifications, presence, edit locks, live tables and chat | Composer |
| [rails](https://github.com/hibira-io/rails) | Rails 7–8, `hibira-rails`: Turbo Streams without Action Cable | RubyGems |
| [godot](https://github.com/hibira-io/godot) | Godot 4.3+, `addons/hibira`: rooms and HibiraSync | GitHub releases |
| [unity](https://github.com/hibira-io/unity) | Unity 2021.3+ incl. WebGL, `io.hibira.realtime` | OpenUPM or git URL |
| [n8n-nodes-hibira](https://github.com/hibira-io/n8n-nodes-hibira) | n8n, `n8n-nodes-hibira`: Hibira and Hibira Trigger nodes | n8n community nodes |
| [terraform-provider-hibira](https://github.com/hibira-io/terraform-provider-hibira) | Terraform, `hibira-io/hibira`: apps, webhooks and push credentials | Terraform Registry |

Each one has a guide at [hibira.io/guides](https://hibira.io/guides), and
runnable demos live in [examples](https://github.com/hibira-io/examples).

The packages were renamed with the brand: `@hikibi/large-presence` and
`@hikibi/push-web` still install but are deprecated, so switch to the
`@hibira-io/*` names.

For public, private and presence channels, keep the Pusher-compatible client you already use and
point it at Hibira.

## 💰 Simple plans

Start free with 100 peak connections and 200,000 messages a day, no credit
card required. Six paid plans run from US$19 to US$699 a month for up to 30,000
peak connections; every plan includes the Pusher protocol, presence and push
notifications. Enterprise plans come with
a 99.9% uptime SLA. See [pricing](https://hibira.io/pricing).

## 💬 Talk to us

- 📖 Docs: [hibira.io/guides](https://hibira.io/guides)
- 🟢 Status: [status.hibira.io](https://status.hibira.io)
- 🐛 SDK bugs: open an issue in the SDK's repository
- 📫 Support: **support@hibira.io**
- 🤝 Sales and Enterprise: **sales@hibira.io** or [contact sales](https://hibira.io/contact-sales)
- 🔒 Security: **security@hibira.io** (please don't open a public issue)
