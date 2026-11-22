OPEN INTEREST / Daily brief, format v2. Sunday, 22 November 2026.

LEAD:
Chainflip halts its cross-chain exchange after a vault payout.

Chainflip put deposits, withdrawals, swaps and quote requests into full safe mode on 21 November 2026 while it investigates a potential vault exploit. [https://www.xitter.gq/Chainflip/status/2124068986845532605] An Ethereum transaction shows its vault sent 520.224339903097753695 ETH, 3,249,631.410561 USDC and 758,141.332716 USDT in one `transferBatch` call. [https://etherscan.io/tx/0xc928950f79b4e4697af674310d1f3a08c2659adc4d60e719f3af90ab023ff20f]

The transaction at the center of the incident was executed at 07:10:59 UTC on 21 November 2026 and called Chainflip's Ethereum vault. [https://etherscan.io/tx/0xc928950f79b4e4697af674310d1f3a08c2659adc4d60e719f3af90ab023ff20f] A signed security advisory independently records the same three token quantities and identifies the transaction as a vault `transferBatch`. [https://www.0xcert.com/advisory/0xCERT-2026-0394] Those quantities are firmer than a dollar estimate because their dollar value changes with the assets' prices. [https://etherscan.io/tx/0xc928950f79b4e4697af674310d1f3a08c2659adc4d60e719f3af90ab023ff20f]

Chainflip's statement does not name an attacker, identify a cause, confirm a loss total, or say when service will return. [https://www.xitter.gq/Chainflip/status/2124068986845532605] The advisory describes the incident as an active exploitation and says the suspected threshold-signature compromise is unconfirmed. [https://www.0xcert.com/advisory/0xCERT-2026-0394] That distinction matters: a valid-looking vault authorization can point to a signing-system failure, but it does not establish how an authorization was obtained. [https://www.0xcert.com/advisory/0xCERT-2026-0394]

Chainflip says each of its four basic functions is disabled, leaving pending cross-chain activity without the normal route to completion. [https://www.xitter.gq/Chainflip/status/2124068986845532605] The record does not yet establish which balances will bear the shortfall, whether other vaults were exposed, or whether the protocol can recover the moved assets. [https://www.xitter.gq/Chainflip/status/2124068986845532605] Those are the unanswered questions, not details to infer from a single transaction.

The transaction establishes a payout from the contract, not who controlled the authorization used to obtain it. [https://etherscan.io/tx/0xc928950f79b4e4697af674310d1f3a08c2659adc4d60e719f3af90ab023ff20f] The 0xCERT advisory says the suspected threshold-signature compromise remains unconfirmed. [https://www.0xcert.com/advisory/0xCERT-2026-0394] Chainflip says its investigation remains in progress. [https://www.xitter.gq/Chainflip/status/2124068986845532605]

NEWS:

[NEWS] Russia opens the door to organised cryptocurrency trading.
[https://www.cbr.ru/press/event/?id=32975]
The Bank of Russia says exchanges may begin cryptocurrency trading from 22 November 2026 once the regulator concurs with their trading rules. [https://www.cbr.ru/press/event/?id=32975] The ordinance requires exchanges to register participants, keep order and transaction records, and monitor trading. [https://www.cbr.ru/press/event/?id=32975] It also requires reporting on trading progress and results under the procedures used for other assets. [https://www.cbr.ru/press/event/?id=32975]

[NEWS] Cyber investigates an unexpected Solana mint and an Ethereum lockbox outflow.
[https://fadect.fun/news/cyber-says-spotted-unexpected-minting-cyber-solana-followed]
Cyber said on 21 November 2026 that it had observed unexpected CYBER minting on Solana followed by CYBER leaving its Ethereum bridge lockbox. [https://fadect.fun/news/cyber-says-spotted-unexpected-minting-cyber-solana-followed] An Ethereum transaction transferred 5,213,000 CYBER from the relevant bridge path at 16:15:11 UTC that day. [https://etherscan.io/tx/0x92a1b430c066cbfb636f67f5354b1720c47e6075523551d9f47bb03bcdc20737] Cyber says it is checking affected assets and routes; it has not published a cause or confirmed loss figure. [https://fadect.fun/news/cyber-says-spotted-unexpected-minting-cyber-solana-followed]

[NEWS] Britain corrects its 2026 cryptoasset regulations.
[https://www.legislation.gov.uk/uksi/2026/1219/pdfs/uksi_20261219_en.pdf]
The Financial Services and Markets Act 2000 (Cryptoassets) (Miscellaneous Amendments) Regulations 2026 were made on 18 November 2026. [https://www.legislation.gov.uk/uksi/2026/1219/pdfs/uksi_20261219_en.pdf] The instrument says it corrects a defect in S.I. 2026/102 and was issued without charge to known recipients. [https://www.legislation.gov.uk/uksi/2026/1219/pdfs/uksi_20261219_en.pdf] Most of the instrument takes effect the day after it was made, while regulations 2 and 3 take effect on 25 October 2027. [https://www.legislation.gov.uk/uksi/2026/1219/pdfs/uksi_20261219_en.pdf]

TECH:

[TECH] Ethlabs argues for an Ethereum post-quantum priority in 2027.
[https://ethlabs.org/writings/pqai27.html]
Ethlabs published its pqai27 position on 11 November 2026, proposing that Ethereum become post-quantum and plausibly post-AI in 2027. [https://ethlabs.org/writings/pqai27.html] The group says that goal would require reordering protocol work and reconsidering features outside the critical path. [https://ethlabs.org/writings/pqai27.html] It presents this as an advocacy position for Ethereum's governance process, not an adopted network schedule. [https://ethlabs.org/writings/pqai27.html]

[TECH] Lightclient makes the case for frame transactions.
[https://lightclient.io/blog/frames-are-all-you-need/]
Lightclient's 5 September 2026 paper argues that Ethereum's fixed transaction authentication scheme should give way to frame transactions. [https://lightclient.io/blog/frames-are-all-you-need/] The proposed model separates validation from execution so accounts can use different authentication and recovery rules. [https://lightclient.io/blog/frames-are-all-you-need/] The article is a design argument, not evidence that a protocol change has been accepted. [https://lightclient.io/blog/frames-are-all-you-need/]

CULTURE:

[CULTURE] The $TRUMP Coin Club stages its holder dinner.
[https://gettrumpmemes.com/gala-dinner]
The project's site schedules its Gala Dinner for 22 November 2026 at Trump National in Washington, D.C. [https://gettrumpmemes.com/gala-dinner] It lists President Donald J. Trump as featured speaker and says 185 top holders may attend. [https://gettrumpmemes.com/gala-dinner] The site says attendees will not receive private meetings with the president, while the top 29 qualifying holders receive a VIP reception. [https://gettrumpmemes.com/gala-dinner]

[CULTURE] Molly White records a poor election return for crypto and AI political spending.
[https://www.citationneeded.news/2026-election-results/]
White reported on 4 November 2026 that crypto and AI companies spent $250 million in the midterms. [https://www.citationneeded.news/2026-election-results/] Her tally found that the PAC-backed side lost nine of 12 competitive races then called. [https://www.citationneeded.news/2026-election-results/] That is White's accounting and interpretation of public election and spending records, not a claim of a settled causal explanation for any result. [https://www.citationneeded.news/2026-election-results/]

READING LIST:
[https://ethlabs.org/writings/pqai27.html] A roster voice's case for moving Ethereum's security timetable ahead.
[https://lightclient.io/blog/frames-are-all-you-need/] A roster voice's explanation of an account-design proposal and its tradeoffs.
[https://www.citationneeded.news/2026-election-results/] Molly White's sourced count of competitive races and political spending.
[https://www.stephendiehl.com/posts/bad_place_2026/] A roster voice's sharply stated policy critique of crypto's political economy.

METHOD:
This 48-hour sweep ending on 22 November 2026 covered protocol notices, public chain records, central-bank and legislation records, masthead writing, and the three latest published editions. [https://openinterest.news/editions.html] [https://raw.githubusercontent.com/openinterest-ai/paper/main/masthead/voices.csv] Reports that assigned a cause to the Chainflip outflow or a confirmed loss to Cyber were cut because the projects have not confirmed either point. [https://www.xitter.gq/Chainflip/status/2124068986845532605] [https://fadect.fun/news/cyber-says-spotted-unexpected-minting-cyber-solana-followed] The Chainflip asset inventory rests in part on the secondary 0xCERT advisory, paired with the cited Ethereum transaction; Cyber's statement is carried by a public relay of its post, paired with the cited Ethereum transaction. [https://www.0xcert.com/advisory/0xCERT-2026-0394] [https://fadect.fun/news/cyber-says-spotted-unexpected-minting-cyber-solana-followed]
