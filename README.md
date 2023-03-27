## Peer to Peer Planning Poker

### [Live site](https://p2ppp.vercel.app)

P2PPP is a proof-of-concept planning poker app using peer-to-peer
[WebRTC data channels][dc] to coordinate voting among players at a
table.

The application is implemented using [Next.js][1] 13, [PeerJS][2],
[Fauna][3] (DB) and is deployed on [Vercel][4].

For another example of a Planning Poker implementation by a colleague
of mine, see [vote.poker][vp] ([code][vpc]).

[dc]: https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Using_data_channels

[1]: https://nextjs.org/

[2]: https://peerjs.com/

[3]: https://fauna.com/

[4]: https://vercel.com/

[vp]: https://vote.poker

[vpc]: https://github.com/chrisemerson/vote.poker

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser
to see the result.

