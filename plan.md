# The plan

Ask drafts. The bot watches. Neither one posts, and neither one treats the classroom as the market.

## The gate

A hunt in [hunts.md](hunts.md) stays a page in this repository until the bot can point at spendable stable money on Kaspa. One of these is enough to open drafting for the counterparties who can receive that coin. Both open the full plan.

**POC opens.** A stranger can receive a POC-style coin. Locking collateral mints it. The holder can redeem. Promotional balances spend before backed balances and do not redeem. No admin key freezes that coin. The rule is something the bot can open: a covenant, a published launch proof, or a later primitive the master file records as spendable. The village tag named POCencept does not open this gate.

**Tether opens.** A stranger can receive a tether-style coin on Kaspa. An issuer mints it. That issuer can freeze that coin, and the freeze does not reach KAS or the POC-style coin. The bot can point at the mint, the freeze rule, and a received payment. The village tag named KUSDT does not open this gate.

**Both open.** A payer can hold one pile that redeems and another pile an issuer can freeze. Hunts that need a clawback use the second pile. Hunts that refuse an issuer key use the first. The same pile can still sit in several hunts of its own kind, and the first snap takes it.

Until then the sentence to say is the master file's sentence: there is no spendable layer-1 stable. KCC-20 remains Draft until the file on kaspanet/kccs says otherwise. A ticker, a thread, or a demo repository stays on the reading list. The gate opens when the bot can follow a payment from a buyer to a stranger in that coin.

## Why the community moves

People who hold Kaspa already want models, cars, connectivity, shares, music, and video. They also want power, rent, food, phones, travel, and the rest of [hunts.md](hunts.md). They will keep paying those bills in whatever the merchant already accepts, for as long as paying in a Kaspa stable means paying alone.

The first company in a category that can receive the stable gives the pack a place to land. The intendos are individual: each person promises their own month, their own car, their own dish, on the condition that enough others promise too and that the company's address can take the coin. When a subset fits, they all pay together. Nobody paid alone into a till that does not exist.

Capital multiplexing is the pressure. The same dollars can be promised to every AI company, every dealer, every carrier, every broker, and every streaming service that might accept. The hunt that snaps first takes the dollars. A company that waits is watching the community pay someone else. That race is endogenous. It needs no campaign.

Composability is how the till gets built. Three hunts stack. Users commit the spend. The company commits to accept the coin and to deliver the thing. The people who wire the till up get paid out of the same snap. If any leg fails its own threshold, nobody moved. A builder is not left maintaining a rail for an empty pack, and a user is not left holding a token for a company that never turned the till on.

Opacity is how a half-built switch survives. Publishing "we are at 12%" lets the incumbent stare at the effort, and lets buyers front-run the snap. The six-pager hides the total on purpose. This desk does not publish pack totals for a hunt that is still a draft.

## Phases

**0. Classroom.** Now. The square runs on Testnet 10. tKAS moves. POCencept and KUSDT are ledger tags. Ask explains them from [rails.md](rails.md). The bot checks the page against the why note. No hunt in [hunts.md](hunts.md) is live.

**1. Watch the gate.** The bot reports when a POC-style coin or a tether-style coin becomes receivable, with the transaction and the master-file commit that records it. Ask keeps describing hunts as drafts. Drafts are written in this repository when the desk asks for a draft. They are answers in a chat until then.

**2. One rail.** The coin that opened the gate can be the unit of new drafts, and only for counterparties who can receive it. A broker who needs a freeze does not get a POC draft forced on them. A buyer who refuses an issuer key does not get a tether draft forced on them. Multiplexing runs across counterparties who take that same coin.

**3. Both rails.** A household can aim the redeemable pile at one set of stags and the freezable pile at another. A freeze of the tether-style coin leaves the POC-style coin and leaves KAS. The purse rule still holds for any promotional balance: it spends first, and it does not redeem into collateral.

**4. Composition.** A user hunt, a merchant hunt, and a payroll hunt for the integration share one snap. Liquidity is allowed to sit in front of them: a stable that cannot be entered or exited in size is still a toy dollar, and Yonatan's liquidity example is the stag that deepens the coin the other hunts spend.

## What Ask does

Ask is the drafter. Given a category, Ask names the stag, the rail, the intendo a person would sign, and the event that snaps. Ask picks the rail from the counterparty's constraint.

- The counterparty can take a coin with no issuer freeze: POC.
- The counterparty needs a freeze or a reversal: KUSDT.
- The counterparty can take either: both, and say which pile multiplexes with which.

Ask speaks the gate in the first answer whenever someone asks to "use Staghunt" for a real bill. The square can be walked today. The bill waits on the coin.

Ask keeps KAS in the answer as collateral under the POC shape and as the fee on the Kaspa transaction. Ask keeps the dollar as the unit inside the intendo.

## What the bot does

The bot is the watcher. It reads the public record and the square. It says what it read: the commit, the status line, the txid, the amount. It says when a page, a note, or this plan has drifted.

Watch list:

- The master-file sentence on spendable layer-1 stables, and the KCC-20 status line.
- Any covenant or issuer transaction that would open the POC gate or the tether gate above. A claim in a reply is weaker than the transaction.
- [sixpack.wtf/1984.html](https://sixpack.wtf/1984.html) against [1984-why-what-how](https://github.com/STP-KAS/1984-why-what-how). Disagreement is reported.
- The freeze boundary, if a tether-style coin appears: a freeze of that coin leaves KAS and leaves the POC-style coin.
- The purse boundary, if a promotional balance appears: it spends before backed coins and does not redeem.

The bot does not mint a guest to read a balance, does not start kaspad, does not retarget miners, does not print a seed or the reserve address, does not change the faucet sentence, and does not post.

## Equations to refuse

- Village POCencept equals a spendable decentralized stable.
- Village KUSDT equals Tether, or any issuer coin a stranger can receive.
- This repository equals Project Staghunt, shipped.
- A drafted hunt equals an intendo on chain.
- staghunt.ai, or the local teaching page, equals the coordination market.
- Live Toccata covenants equal a hidden pack and a threshold snap.
- A KCC-20 draft, or a demo mint, equals an open gate.
- "The community will go there" equals a fact about a named company. It is the incentive inside multiplexing, and it happens after that company can receive the coin and a subset's thresholds clear.
