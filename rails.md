# The three rails

Read on 30 Sep 2026 against [sixpack.wtf/1984.html](https://sixpack.wtf/1984.html) and [STP-KAS/1984-why-what-how](https://github.com/STP-KAS/1984-why-what-how). If the page and that note disagree, say so. This file is the economics. The page note is the visit.

The rails exist so a bill can be paid. The bills in front of this desk are a car, an AI service, a game purchase, and a rented service. [hunts.md](hunts.md) drafts those shapes. The square can walk a toy version. A stranger still cannot receive the unit those bills are priced in. [plan.md](plan.md) stays at the classroom until that receive exists.

KCC-20 is still Draft. The master file still says there is no spendable layer-1 stable. The till in the square compiles no SilverScript covenant. A shop row is a village ledger row. Coffee is a purchase in that ledger. A vProg guest sequences a declared ply in tic-tac-toe. The square does not sequence coffee.

## What each rail is for

Money in the square has four jobs. The three names split those jobs so a person can see them.

| Job | Where it sits | What you learn |
| --- | --- | --- |
| Unit of account | Toy cents on POCencept and KUSDT | Coffee stays 2.50 while the KAS quote moves |
| Coin that moves | tKAS, a Testnet-10 transaction | A lock, a redeem, and a tKAS shop payment are chain events |
| Fee | Extra tKAS, outside the price | The miner is paid even when the tag never touches the chain |
| Freeze | KUSDT only | An issuer switch can stop one stable and leave the other coin and the base coin spendable |

**tKAS** is native Testnet-10 Kaspa. A bank lock sends it to the reserve. A redeem sends it back. A shop paid on the tKAS rail sends it too. The miner fee is extra tKAS and sits outside the price. Mainnet is refused.

**POCencept** is a proof-of-concept stable tag, quoted in toy cents, so a shop can be paid while tKAS stays put. The practice behind the name is older desk work: grams as prepaid mass, PegLab as the classroom where a thin peg breaks, Ishum as a quote that settles KAS, and BitCoffee as a Testnet-10 covenant dollar this desk left where it was written. This square did not re-mint those assets. POCencept has no freeze.

**KUSDT** is a tether-style tag in the same ledger. The booth exists so a freeze can be seen. Freeze blocks new KUSDT spends and KUSDT swaps. POCencept still pays. tKAS still pays. A freeze does not reach the other two.

## On chain, today

A tKAS movement is a Testnet-10 transaction.

The wallet signs a tKAS bank swap only when that wallet's account is the address already on the page. A different address does not sign. A mainnet account does not sign. With Kasware or Kastle logged in, the shop's tKAS rail does not sign. A shop buy, and a POCencept or KUSDT swap, ask on the page: you want this for that price, then OK.

Every Testnet-10 send pays twice the ordinary fee the node quotes. The quiet standard is 100 sompi per gram, so the quiet send pays 200. A higher ordinary quote is doubled from there. The floor stays 200. A wallet payment also adds 0.02 tKAS so a wallet that only understands a flat fee still clears that double rate. The page reads the doubled rate from the till before a wallet lock signs. If that read fails, the page still asks for 200. The faucet still pays 0.6 tKAS. The miner fee is extra.

The till looks for the payment on the public Testnet-10 list. That list stopped storing new payments on 25 Sep 2026 (`acceptedTxBlockTime` 25 Sep 2026 19:55:38Z). When the list does not have the payment, the server reads about the last minute of accepted blocks from a synced node. The sender has to be the address on the page. The reserve output has to cover the quote. A payment still only in the mempool is retried and is not credited. A payment older than about a minute is outside this check. The same transaction does not mint the tag twice. A short payment is refused. The txid stays in the paste box when the till has not claimed it, so the next Lock uses that transaction.

POCencept and KUSDT do not appear in a Kaspa transaction. They are balances in the ledger that runs beside the sixpack server. GitHub Pages serves the page and cannot run that ledger. The shop card says the buy is this square's own ledger. A tKAS bank swap says the txid is the Testnet-10 payment.

The rules panel is a stand-in you can click. A covenant, in the sense SilverScript and the Kaspero Labs freelancer sheet use the word, is a rule the Kaspa network enforces on the coins. The sheet holds the coins. 1984's server holds the toy ledger. That is the gap this plan is waiting on.

## The economics

Prices in the shops are toy cents. Coffee is 2.50, supper is 14.00, the roadster is 1.00, a lap of the square is 100.00. The launch is free. At a full bar the Moon is 2.00, Mars is 5.00, Jupiter is 8.00, and Saturn is 12.00. Those cent prices stay put when the KAS quote moves. On the tKAS rail the till converts the cents with the live KAS/USD quote shown on the page, and rounds the sompi up so the reserve is not short.

The conversion in the till is: take the dollar price of one KAS in millionths, multiply by the sompi, and divide by 1,000,000,000,000. That yields cents. One toy dollar is 100 cents. At a quote of $0.05 per KAS, one tKAS is 5 cents, and one toy dollar is 20 tKAS. The page uses the live quote. The $0.05 line is the arithmetic check, so a reader can see the unit.

**Lock.** tKAS leaves the wallet. The till credits the same cents as locked POCencept or locked KUSDT, at that quote. Locked toy dollars are a claim on tKAS that was sent. The live quote and the reserve sit on the bank's fine line. This file does not print the reserve address.

**Purse.** The books desk can add 20.00 POCencept and 20.00 KUSDT. Those coins are unlocked. They are play money. A shop burns the purse before it burns the locked part. The purse does not redeem. A swap between POCencept and KUSDT moves locked cents to locked and purse cents to purse. It does not change how much tKAS the till owes.

**Redeem.** Only the locked part comes back as tKAS. One redeem is at most 10,000 tKAS. The whole process is at most 1,000,000 tKAS. The smallest redeem is 0.01 tKAS. A failed redeem puts the toy balance back. Burning and spending are the same word here: the cents leave, and only the backed cents pull tKAS out of the reserve.

**The peg.** The quote is an outside price. If it moves, a redeem can fail because the locked tKAS no longer covers the toy dollars. That is a peg failing. The page says so, in the PegLab line. The tag is a quote against locked tKAS. A dollar claim that a stranger can receive begins when the collateral and the rule live on the network, a reader can open the covenant, and a payment in that coin can be followed.

**The freeze.** KUSDT can be frozen at its booth. Frozen KUSDT does not buy and does not swap. POCencept and tKAS are unchanged. That is the whole tether lesson at toy size: an issuer switch is useful to a merchant who must reverse or seize one coin, and the base coin and the other stable stay spendable.

**The fee.** The price is the shop. The fee is the proof-of-work network. Doubling the ordinary rate is a choice so a busy Testnet-10 mempool is less likely to hold the send. It is extra tKAS. It is not a second price.

## What a real stable has to keep

A POC-style coin, when it exists as money, keeps the lock, the redeem, the purse rule, and the peg warning. Collateral moves on Kaspa. The holder can redeem. Promotional balances spend first and do not redeem. No admin key freezes that coin. The rule is on the coin.

A tether-style coin, when it exists as money, keeps the freeze boundary. The issuer can stop that coin. The issuer cannot stop KAS, and cannot stop the POC-style coin, by freezing KUSDT.

Both can exist together. A person holds the one the counterparty accepts. A broker, a lender, or a marketplace under a court may accept only the coin it can freeze. A buyer who will not hand an issuer that power pays in the coin that redeems. A counterparty who accepts both lets the payer choose. The square already spends them side by side. The plan in [plan.md](plan.md) waits until at least one of them is receivable outside the ledger.
