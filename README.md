# Cricket Auction Night

**Two bidders. 200 points each. One screen. Only one champion.**

A two-player cricket auction game that runs in the browser. It started as a Papa vs Son Excel sheet at the dining table and grew into a full auction with a bidding clock, a gavel, legend coaches and confetti.

**Play it here:** https://YOUR-USERNAME.github.io/cricket-auction-night/

## How it works

- **Spin the hammer.** A random player comes up for auction. Bidding opens at his base price.
- **Bid against the clock.** Every bid resets the 10-second timer. Then it's *going once… going twice… SOLD!*
- **Fast hammer.** If nobody can afford the player, or nobody can raise the current bid, the clock drops to 3 seconds.
- **Build a valid XI.** You need 11 players, including at least 1 wicket-keeper, 3 bowlers and 1 all-rounder, with no more than 5 from one country.
- **Sign legend coaches.** Sachin, Warne, Lara, Dhoni and 8 more appear on golden cards. Each team can sign up to 2 coaches, and legends stop appearing once both teams have their 2.
- **Use your power cards.** Each bidder gets one of each:
  - **RTM card:** match the winning price and steal the player.
  - **Strategic timeout:** freeze the clock for 20 seconds to think.
- **Unsold round.** Leftover players come back at half price.
- **Reveal the secret ratings.** Team power decides the winner, and bargain buys can beat big spending.
- **Did you know?** Cricket trivia appears between lots, and every legend card has its own legend fact.

## Scoring

**Team power** is the total of:

| Part | Points |
|---|---|
| Player ratings | Secret rating of each player in your XI |
| Captain | His rating counts twice |
| Coach power | Legend's rating + speciality boost: Batting +3 per Batter, Bowling +3 per Bowler, All-round +5 per All-rounder, Keeping +10 per Wicket-keeper |
| Balanced XI | +10 if all squad rules are met |
| Steal of the auction | +5 for the team that bought the best rating for the price |
| World XI | +5 for players from 5 or more countries |
| Smart money | +1 for every 5 points left unspent |
| Rule penalty | −15 for each broken squad rule |

| Tier | Base price |
|---|---|
| Legend (coach) | 12 pts |
| Platinum | 20 pts |
| Gold | 15 pts |
| Silver | 10 pts |
| Bronze | 6 pts |
| Rising Star | 3 pts |

## Keyboard shortcuts

| Action | Key |
|---|---|
| Spin / next lot | `Space` |
| Left bidder: bid / +5 | `A` / `S` |
| Right bidder: bid / +5 | `L` / `K` |
| Bang the gavel (sell now) | `G` |
| Mark unsold (no bids) | `U` |
| Pause / resume clock | `P` |
| Strategic timeout (left / right) | `Q` / `O` |
| RTM: match / let go | `Y` / `N` |

On a phone or tablet, tap the buttons.

## Adding player photos (optional)

The game shows illustrated avatars by default. If you have photos you're allowed to use, it shows them instead:

1. Create a folder called `images` in this repository, next to `index.html`.
2. Save each photo as a **.jpg** with the exact file name from the list below.
3. Square photos with the face near the top work best. Around 300 × 300 pixels is plenty.

Any player without a photo keeps his avatar, so you can add photos a few at a time.

Only use photos you have the right to use. [Wikimedia Commons](https://commons.wikimedia.org) has many cricketer photos under free licences. Check each photo's licence and credit the photographer in the list below.

<details>
<summary>All 84 file names</summary>

| Player | File name |
|---|---|
| Sachin Tendulkar | `images/sachin-tendulkar.jpg` |
| Shane Warne | `images/shane-warne.jpg` |
| Brian Lara | `images/brian-lara.jpg` |
| Sir Viv Richards | `images/sir-viv-richards.jpg` |
| Jacques Kallis | `images/jacques-kallis.jpg` |
| Kapil Dev | `images/kapil-dev.jpg` |
| MS Dhoni | `images/ms-dhoni.jpg` |
| Adam Gilchrist | `images/adam-gilchrist.jpg` |
| Muttiah Muralitharan | `images/muttiah-muralitharan.jpg` |
| Glenn McGrath | `images/glenn-mcgrath.jpg` |
| Ricky Ponting | `images/ricky-ponting.jpg` |
| Rahul Dravid | `images/rahul-dravid.jpg` |
| Virat Kohli | `images/virat-kohli.jpg` |
| Jasprit Bumrah | `images/jasprit-bumrah.jpg` |
| Rohit Sharma | `images/rohit-sharma.jpg` |
| Shubman Gill | `images/shubman-gill.jpg` |
| Travis Head | `images/travis-head.jpg` |
| Joe Root | `images/joe-root.jpg` |
| Pat Cummins | `images/pat-cummins.jpg` |
| Rashid Khan | `images/rashid-khan.jpg` |
| Hardik Pandya | `images/hardik-pandya.jpg` |
| Ravindra Jadeja | `images/ravindra-jadeja.jpg` |
| Rishabh Pant | `images/rishabh-pant.jpg` |
| Yashasvi Jaiswal | `images/yashasvi-jaiswal.jpg` |
| Suryakumar Yadav | `images/suryakumar-yadav.jpg` |
| Harry Brook | `images/harry-brook.jpg` |
| Ben Stokes | `images/ben-stokes.jpg` |
| Jos Buttler | `images/jos-buttler.jpg` |
| Mitchell Starc | `images/mitchell-starc.jpg` |
| Steve Smith | `images/steve-smith.jpg` |
| Josh Hazlewood | `images/josh-hazlewood.jpg` |
| Kagiso Rabada | `images/kagiso-rabada.jpg` |
| Marnus Labuschagne | `images/marnus-labuschagne.jpg` |
| Mohammed Shami | `images/mohammed-shami.jpg` |
| Kane Williamson | `images/kane-williamson.jpg` |
| Kuldeep Yadav | `images/kuldeep-yadav.jpg` |
| Arshdeep Singh | `images/arshdeep-singh.jpg` |
| Abhishek Sharma | `images/abhishek-sharma.jpg` |
| KL Rahul | `images/kl-rahul.jpg` |
| Mohammed Siraj | `images/mohammed-siraj.jpg` |
| Axar Patel | `images/axar-patel.jpg` |
| Varun Chakaravarthy | `images/varun-chakaravarthy.jpg` |
| Cameron Green | `images/cameron-green.jpg` |
| Mitchell Marsh | `images/mitchell-marsh.jpg` |
| Glenn Maxwell | `images/glenn-maxwell.jpg` |
| Jofra Archer | `images/jofra-archer.jpg` |
| Phil Salt | `images/phil-salt.jpg` |
| Rachin Ravindra | `images/rachin-ravindra.jpg` |
| Daryl Mitchell | `images/daryl-mitchell.jpg` |
| Trent Boult | `images/trent-boult.jpg` |
| Aiden Markram | `images/aiden-markram.jpg` |
| Marco Jansen | `images/marco-jansen.jpg` |
| Ryan Rickelton | `images/ryan-rickelton.jpg` |
| Wanindu Hasaranga | `images/wanindu-hasaranga.jpg` |
| Sanju Samson | `images/sanju-samson.jpg` |
| Tilak Varma | `images/tilak-varma.jpg` |
| Adam Zampa | `images/adam-zampa.jpg` |
| Josh Inglis | `images/josh-inglis.jpg` |
| Adil Rashid | `images/adil-rashid.jpg` |
| Jamie Smith | `images/jamie-smith.jpg` |
| Mitchell Santner | `images/mitchell-santner.jpg` |
| Matt Henry | `images/matt-henry.jpg` |
| Quinton de Kock | `images/quinton-de-kock.jpg` |
| Keshav Maharaj | `images/keshav-maharaj.jpg` |
| Dewald Brevis | `images/dewald-brevis.jpg` |
| Lockie Ferguson | `images/lockie-ferguson.jpg` |
| Rahmanullah Gurbaz | `images/rahmanullah-gurbaz.jpg` |
| Azmatullah Omarzai | `images/azmatullah-omarzai.jpg` |
| Pathum Nissanka | `images/pathum-nissanka.jpg` |
| Shai Hope | `images/shai-hope.jpg` |
| Mehidy Hasan Miraz | `images/mehidy-hasan-miraz.jpg` |
| Mustafizur Rahman | `images/mustafizur-rahman.jpg` |
| Nitish Kumar Reddy | `images/nitish-kumar-reddy.jpg` |
| Harshit Rana | `images/harshit-rana.jpg` |
| Jake Fraser-McGurk | `images/jake-fraser-mcgurk.jpg` |
| Jacob Bethell | `images/jacob-bethell.jpg` |
| Tristan Stubbs | `images/tristan-stubbs.jpg` |
| Sai Sudharsan | `images/sai-sudharsan.jpg` |
| Noor Ahmad | `images/noor-ahmad.jpg` |
| Matheesha Pathirana | `images/matheesha-pathirana.jpg` |
| Kusal Mendis | `images/kusal-mendis.jpg` |
| Alzarri Joseph | `images/alzarri-joseph.jpg` |
| Romario Shepherd | `images/romario-shepherd.jpg` |
| Litton Das | `images/litton-das.jpg` |

</details>

### Photo credits

<!-- Add one line per photo, for example: -->
<!-- - Virat Kohli: Photo by NAME, CC BY-SA 4.0, Wikimedia Commons -->

## Run it yourself

The whole game is one file, `index.html`, with no installs, build steps or servers. Download it and open it in any browser, or host it free on GitHub Pages.

## Fine print

This is a fan-made game for family fun. Prices and ratings are virtual points made up for the game. They are not real auction values or official ratings, and the game has no link to any cricket board, league or player. There is no real money and no betting. The loser makes the chai, and that's the only forfeit.
