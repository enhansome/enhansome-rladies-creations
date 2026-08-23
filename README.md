<!-- README.md is generated from README.Rmd. Please edit that file -->

# Awesome RLadies+ Content and Packages with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated lists of RLadies+ community resources (blogs, YouTube channels,
and R packages currently). Each entry is stored as a JSON metadata file
in this repository; the site-friendly aggregated JSON files are
generated into the `data/website/` directory by the script
`scripts/generate_website_jsons.R`.

To contribute: add a JSON file describing the blog (to `data/content/`)
or the package (to `data/packages/`) following the examples in the
repository and the JSON schema at `scripts/json_schema/`.

See `CONTRIBUTING.md` for style and metadata conventions.

## List of blogs

Created from the JSON files in `data/content/` (one JSON per blog). The
aggregated file is written to `data/website/awesome_content.json`.

* [Amanda’s Data Blog](amanda.rbind.io) by Amanda Peterson
* [Very Statisticious](https://aosmith.rbind.io) by Ariel Muldoon
* [Alison Hill](https://www.apreshill.com) by Alison Hill
* [Beatriz Milz’s blog](https://beatrizmilz.com/) by Beatriz Milz
* [Notes from a data witch](https://blog.djnavarro.net/) by Danielle
  Navarro
* [Emma R](https://buzzrbeeline.blog/) by Emma Rand
* [Building Stories with Data](https://cararthompson.com/blog) by Cara
  Thompson
* [Crystal Lewis](https://www.cghlewis.com) by Crystal Lewis
* [Citizen Statistician](citizen-statistician.org) by Mine
  Çetinkaya-Rundel, Rob Gould, Andrew Zieffler
* [Cosima Meyer](https://cosimameyer.com/) by Cosima Meyer
* [Cynthia D’Angelo](https://cynthiadangelo.com/) by Cynthia D’Angelo
* [Darya Vanichkina’s blog](https://www.daryavanichkina.com/posts.html)
  by Darya Vanichkina
* [Data Pedagogy](https://www.datapedagogy.com/) by Mine Dogucu
* [Dr. Mowinckel’s blog](https://drmowinckels.io) by Athanasia Monika
  Mowinckel
* [Elena Dudukina’s blog](https://elenadudukina.com) by Elena Dudukina
* [Ella Kaye](https://ellakaye.co.uk) by Ella Kaye
* [Emily Riederer](https://emilyriederer.com) by Emily Riederer
* [Estatística | Fernanda Kelly Romeiro
  Silva](https://www.fernandakellyrs.com/) by Fernanda Kelly Romeiro
  Silva
* [Federica Gazzelloni](https://fgazzelloni.quarto.pub) by Federica
  Gazzelloni
* [Site | FLORENCIA GRATTAROLA](https://flograttarola.com/) by
  Florencia Grattarola
* [Florencia D’Andrea](https://florenciadandrea.com) by Florencia
  D’Andrea
* [helena \* jambor](https://helenajambor.wordpress.com/) by Helena
  Jambor
* [Hypebright](https://hypebright.nl/index.php/en/home-en/blog/) by
  Veerle van Leemput
* [Isabel Zimmerman](https://isabelizimm.github.io/) by Isabel Zimmerman
* [%>% Dreams](https://ivelasq.rbind.io/) by Isabella Velásquez
* [data whiskeRs](https://jadeyryan.com/blog) by Jadey Ryan
* [Data in life](https://jhylin.github.io/Data_in_life_blog/) by
  Jennifer HY Lin
* [JRaviLab](https://jravilab.github.io/) by Janani Ravi
* [Julia Silge](https://juliasilge.com/) by Julia Silge
* [Karina Bartolome](https://karbartolome-blog.netlify.app) by Karina
  Bartolome
* [Once Upon a Time
  Series](https://lgibson7.quarto.pub/once-upon-a-time-series/) by Lydia
  Gibson
* [Lore Abad](https://loreabad6.github.io/) by Lorena Abad
* [Macarena Quiroga](https://macarenaquiroga.netlify.app) by Macarena
  Quiroga
* [Maëlle’s R blog](https://masalmon.eu/) by Maëlle Salmon
* [Nicola Rennie](https://nrennie.rbind.io) by Nicola Rennie
* [Pao Corrales](https://paocorrales.github.io/) by Pao Corrales
* [Piping Hot Data](https://www.pipinghotdata.com) by Shannon Pileggi
* [R-Ladies Gaborone](https://r-ladiesgaborone2021.quarto.pub) by
  R-Ladies Gabarone
* [R-Ladies Melbourne Blog](https://r-ladiesmelbourne.github.io/) by
  R-Ladies Melbourde
* [Rizqy Amelia Zein](https://rameliaz.github.io/) by Rizqy Amelia Zein
* [Riinu’s scripting diary](https://www.riinu.me/) by Riinu Pius
* [R-Ladies São Paulo Blog](https://rladies-sp.org/) by R-Ladies São
  Paulo
* [RLadies+ Global Blog](https://rladies.org/blog/) by RLadies+
* [Data Science
  Blog](https://sabrinaschalz.wordpress.com/data-science-blog/) by
  Sabrina Schalz
* [Sarah Gillespie’s blog](https://sarahgillespie.github.io/SG/) by
  Sarah Gillespie
* [Sam Tyner-Monroe](https://sctyner.me) by Sam Tyner-Monroe
* [Shel Kariuki’s blog](https://shelkariuki.netlify.app/) by Shel
  Kariuki
* [Meeting People Where They R](https://silviacanelon.com) by Silvia
  Canelón
* [Data by Andre blog](https://soyandrea.github.io/) by Andrea Gomez
  Vargas
* [Ciencia de Datos en Español](https://sporella.xyz) by Steph Orellana
  Bello
* [Steffi LaZerte](https://steffilazerte.ca/tips_and_tricks.html) by
  Steffi LaZerte
* [Surrounded by Data](https://surroundedbydata.netlify.app/) by Veerle
  van Son
* [Exploration Corner](https://thetidytrekker.com/blog.html) by Meghan
  Harris
* [Willing Consulting](https://www.willingconsulting.com/) by Carol
  Willing
* [Yanina Bellini Saibene](https://yabellini.netlify.app/blog/) by
  Yanina Bellini Saibene
* [Melissa Van Bussel (ggnot2)’s YouTube channel about
  R](https://www.youtube.com/c/ggnot2) by Melissa Van Bussel

## List of packages

Created from the JSON files in `data/packages/` (one JSON per package).
The aggregated file is written to `data/website/awesome_packages.json`.

* [h2o](https://github.com/h2oai/h2o-3) ⭐ 7,495 | 🐛 2,883 | 🌐 Jupyter Notebook | 📅 2026-08-23 by Tomas Fryda, Erin LeDell,
  Navdeep Gill, Spencer Aiello, Anqi Fu, Arno Candel, Cliff Click, Tom
  Kraljevic, Tomas Nykodym, Patrick Aboyoun, Michal Kurka, Michal
  Malohlava, Sebastien Poirier, Wendy Wong, Ludi Rehak, Eric Eckstrand,
  Brandon Hill, Sebastian Vidrio, Surekha Jadhawani, Amy Wang, Raymond
  Peck, Jan Gorecki, Matt Dowle, Yuan Tang, Lauren DiPerna, Veronika
  Maurerova, Yuliia Syzon, Adam Valenta, Marek Novotny, H2O.ai
* [ggplot2](https://github.com/tidyverse/ggplot2) ⭐ 6,983 | 🐛 145 | 🌐 R | 📅 2026-04-22 by Hadley Wickham,
  Winston Chang, Lionel Henry, Thomas Lin Pedersen, Kohske Takahashi,
  Claus Wilke, Kara Woo, Hiroaki Yutani, Dewey Dunnington, Teun van den
  Brand, Posit, PBC
* [devtools](https://github.com/r-lib/devtools) ⭐ 2,518 | 🐛 6 | 🌐 R | 📅 2026-08-18 by Hadley Wickham, Jim
  Hester, Winston Chang, Jennifer Bryan, Posit Software, PBC
* [blogdown](https://github.com/rstudio/blogdown) ⭐ 1,793 | 🐛 29 | 🌐 R | 📅 2026-06-19 by Yihui Xie,
  Christophe Dervieux, Alison Presmanes Hill, Amber Thomas, Beilei Bian,
  Brandon Greenwell, Brian Barkley, Deependra Dhakal, Eric Nantz, Forest
  Fang, Garrick Aden-Buie, Hiroaki Yutani, Ian Lyttle, Jake Barlow,
  James Balamuta, JJ Allaire, Jon Calder, Jozef Hajnala, Juan Manuel
  Vazquez, Kevin Ushey, Leonardo Collado-Torres, Maëlle Salmon, Maria
  Paula Caldas, Nicolas Roelandt, Oliver Madsen, Raniere Silva, TC
  Zhang, Xianying Tan, Posit Software, PBC
* [gtsummary](https://github.com/ddsjoberg/gtsummary) ⭐ 1,207 | 🐛 18 | 🌐 R | 📅 2026-08-21 by Daniel D.
  Sjoberg, Joseph Larmarange, Michael Curry, Emily de la Rua, Jessica
  Lavery, Karissa Whiting, Emily C. Zabor, Xing Bai, Malcolm Barrett,
  Esther Drill, Jessica Flynn, Margie Hannum, Stephanie Lobaugh, Shannon
  Pileggi, Amy Tin, Gustavo Zapata Wainberg
* [tidytext](https://github.com/juliasilge/tidytext) ⭐ 1,201 | 🐛 8 | 🌐 R | 📅 2026-08-02 by Gabriela De
  Queiroz, Colin Fay, Emil Hvitfeldt, Os Keyes, Kanishka Misra, Tim
  Mastny, Jeff Erickson, David Robinson, Julia Silge
* [skimr](https://github.com/ropensci/skimr/) ⭐ 1,141 | 🐛 20 | 🌐 HTML | 📅 2026-01-08 by Elin Waring, Michael
  Quinn, Amelia McNamara, Eduardo Arino de la Rubia, Hao Zhu, Julia
  Lowndes, Shannon Ellis, Hope McLeod, Hadley Wickham, Kirill Müller,
  RStudio, Inc., Connor Kirkpatrick, Scott Brenstuhl, Patrick Schratz,
  lbusett, Mikko Korpela, Jennifer Thompson, Harris McGehee, Mark
  Roepke, Patrick Kennedy, Daniel Possenriede, David Zimmermann, Kyle
  Butts, Bastian Torges, Rick Saporta, Henry Morgan Stewart, Olivier Roy
* [readr](https://github.com/tidyverse/readr) ⭐ 1,038 | 🐛 102 | 🌐 R | 📅 2026-04-10 by Hadley Wickham, Jim
  Hester, Romain Francois, Jennifer Bryan, Shelby Bearrows, Posit
  Software, PBC, <https://github.com/mandreyel/>, Jukka Jylänki, Mikkel
  Jørgensen
* [palmerpenguins](https://github.com/allisonhorst/palmerpenguins) ⭐ 1,015 | 🐛 18 | 🌐 R | 📅 2024-09-19 by
  Allison Horst, Alison Hill, Kristen Gorman
* [rsparkling](https://github.com/h2oai/sparkling-water/tree/master/r) ⭐ 979 | 🐛 43 | 🌐 Scala | 📅 2025-11-05
  by Jakub Hava, Navdeep Gill, Erin LeDell, Michal Malohlava, JJ
  Allaire, H2O.ai, RStudio
* [usethis](https://github.com/r-lib/usethis) ⭐ 920 | 🐛 91 | 🌐 R | 📅 2026-07-14 by Hadley Wickham,
  Jennifer Bryan, Malcolm Barrett, Andy Teucher, Posit Software, PBC
* [infer](https://github.com/tidymodels/infer) ⭐ 795 | 🐛 7 | 🌐 R | 📅 2026-04-13 by Andrew Bray, Chester
  Ismay, Evgeni Chasnovski, Simon Couch, Ben Baumer, Mine
  Cetinkaya-Rundel, Ted Laderas, Nick Solomon, Johanna Hardin, Albert Y.
  Kim, Neal Fultz, Doug Friedman, Richie Cotton, Brian Fannin
* [pkgdown](https://github.com/r-lib/pkgdown) ⭐ 773 | 🐛 103 | 🌐 R | 📅 2026-08-12 by Hadley Wickham, Jay
  Hesselberth, Maëlle Salmon, Olivier Roy, Salim Brüggemann, Posit
  Software, PBC
* [readxl](https://github.com/tidyverse/readxl) ⭐ 752 | 🐛 51 | 🌐 C++ | 📅 2026-05-17 by Hadley Wickham,
  Jennifer Bryan, Posit, PBC, Marcin Kalicinski, Komarov Valery,
  Christophe Leitienne, Bob Colbert, David Hoerl, Evan Miller
* [reprex](https://github.com/tidyverse/reprex) ⭐ 752 | 🐛 29 | 🌐 R | 📅 2026-04-10 by Jennifer Bryan, Jim
  Hester, David Robinson, Hadley Wickham, Christophe Dervieux, Posit
  Software, PBC
* [glue](https://github.com/tidyverse/glue) ⭐ 750 | 🐛 7 | 🌐 R | 📅 2026-04-21 by Jim Hester, Jennifer
  Bryan, Posit Software, PBC
* [phyloseq](https://github.com/joey711/phyloseq) ⭐ 652 | 🐛 769 | 🌐 R | 📅 2026-02-27 by Paul J. McMurdie,
  Susan Holmes, Gregory Jordan, Scott Chamberlain
* [vroom](https://github.com/tidyverse/vroom) ⭐ 642 | 🐛 67 | 🌐 C++ | 📅 2026-06-09 by Jim Hester, Hadley
  Wickham, Jennifer Bryan, Shelby Bearrows,
  <https://github.com/mandreyel/>, Jukka Jylänki, Mikkel Jørgensen,
  Posit Software, PBC
* [igraph](https://github.com/igraph/rigraph) ⭐ 620 | 🐛 171 | 🌐 R | 📅 2026-08-22 by Gábor Csárdi, Tamás
  Nepusz, Vincent Traag, Szabolcs Horvát, Fabio Zanini, Daniel Noom,
  Kirill Müller, Michael Antonov, Chan Zuckerberg Initiative, David
  Schoch, Maëlle Salmon, R Consortium
* [dada2](https://github.com/benjjneb/dada2) ⭐ 555 | 🐛 217 | 🌐 R | 📅 2026-07-31 by Benjamin Callahan
  <benjamin.j.callahan@gmail.com>, Paul McMurdie, Susan Holmes
* [mice](https://github.com/amices/mice) ⭐ 516 | 🐛 30 | 🌐 R | 📅 2026-07-07 by Stef van Buuren, Karin
  Groothuis-Oudshoorn, Gerko Vink, Rianne Schouten, Alexander Robitzsch,
  Patrick Rockenschaub, Lisa Doove, Shahab Jolani, Margarita
  Moreno-Betancur, Ian White, Philipp Gaffert, Florian Meinfelder,
  Bernie Gray, Vincent Arel-Bundock, Mingyang Cai, Thom Volker, Edoardo
  Costantini, Caspar van Lissa, Hanne Oberman, Stephen Wade, Florian van
  Leeuwen, Frederik Fabricius-Bjerre
* [goodpractice](https://github.com/ropensci-review-tools/goodpractice) ⭐ 480 | 🐛 7 | 🌐 R | 📅 2026-07-29
  by Mark Padgham, Ascent Digital Services UK Limited, Karina Marks,
  Daniel de Bortoli, Gabor Csardi, Hannah Frick, Owen Jones, Hannah
  Alexander, Ana Simmons, Fabian Scheipl
* [h2o4gpu](https://github.com/h2oai/h2o4gpu) ⭐ 468 | 🐛 157 | 🌐 C++ | 📅 2026-07-27 by Yuan Tang, Navdeep
  Gill, Erin LeDell, Vladimir Ovsyannikov, H2O.ai
* [emmeans](https://github.com/rvlenth/emmeans/) ⭐ 425 | 🐛 5 | 🌐 R | 📅 2026-08-18 by Russell V. Lenth,
  Julia Piaskowski, Balazs Banfai, Ben Bolker, Paul Buerkner, Iago
  Giné-Vázquez, Maxime Hervé, Maarten Jung, Jonathon Love, Fernando
  Miguez, Hannes Riebl, Henrik Singmann
* [shinyMobile](https://github.com/RinteRface/shinyMobile) ⭐ 423 | 🐛 71 | 🌐 R | 📅 2026-06-13 by David
  Granjon, Veerle van Leemput, AthlyticZ, Victor Perrier, John Coene,
  Isabelle Rudolf, Dieter Menne, Marvelapp, Vladimir Kharlampidi
* [sfnetworks](https://github.com/luukvdmeer/sfnetworks) ⭐ 398 | 🐛 28 | 🌐 R | 📅 2026-05-14 by Lucas van
  der Meer, Lorena Abad, Andrea Gilardi, Robin Lovelace
* [aws.s3](https://github.com/cloudyr/aws.s3) ⭐ 384 | 🐛 95 | 🌐 R | 📅 2025-08-18 by Thomas J. Leeper,
  Boettiger Carl, Andrew Martin, Mark Thompson, Tyler Hunt, Steven
  Akins, Bao Nguyen, Thierry Onkelinx, Andrii Degtiarov, Dhruv Aggarwal,
  Alyssa Columbus, Simon Urbanek
* [googlesheets4](https://github.com/tidyverse/googlesheets4) ⭐ 375 | 🐛 37 | 🌐 R | 📅 2026-08-23 by
  Jennifer Bryan, Posit Software, PBC
* [rhub](https://github.com/r-hub/rhub) ⭐ 366 | 🐛 46 | 🌐 R | 📅 2025-03-07 by Gábor Csárdi, Maëlle Salmon,
  R Consortium
* [cowsay](https://github.com/sckott/cowsay) ⭐ 351 | 🐛 3 | 🌐 HTML | 📅 2025-10-29 by Scott Chamberlain,
  Amanda Dobbyn, Tyler Rinker, Thomas Leeper, Noam Ross, Rich FitzJohn,
  Carson Sievert, Kiyoko Gotanda, Andy Teucher, Karl Broman,
  Franz-Sebastian Krah, Lucy D’Agostino McGowan, Guangchuang Yu, Philipp
  Boersch-Supan, Andreas Brandmaier, Marion Louveaux, David Schoch
* [datasauRus](https://github.com/jumpingrivers/datasauRus) ⭐ 345 | 🐛 1 | 🌐 R | 📅 2025-01-23 by Colin
  Gillespie, Steph Locke, Alberto Cairo, Rhian Davies, Justin Matejka,
  George Fitzmaurice, Lucy D’Agostino McGowan, Richard Cotton, Tim Book,
  Jumping Rivers
* [googledrive](https://github.com/tidyverse/googledrive) ⭐ 345 | 🐛 41 | 🌐 R | 📅 2026-08-23 by Lucy
  D’Agostino McGowan, Jennifer Bryan, Posit Software, PBC
* [slingshot](https://github.com/kstreet13/slingshot) ⭐ 344 | 🐛 8 | 🌐 R | 📅 2024-04-23 by Kelly Street,
  Davide Risso, Diya Das, Sandrine Dudoit, Koen Van den Berge, Robrecht
  Cannoodt
* [rsample](https://github.com/tidymodels/rsample) ⭐ 343 | 🐛 36 | 🌐 R | 📅 2026-04-14 by Hannah Frick,
  Fanny Chow, Max Kuhn, Michael Mahoney, Julia Silge, Hadley Wickham,
  Posit Software, PBC
* [osmdata](https://github.com/ropensci/osmdata) ⭐ 342 | 🐛 25 | 🌐 R | 📅 2026-07-18 by Joan Maspons, Mark
  Padgham, Bob Rudis, Robin Lovelace, Maëlle Salmon, Andrew Smith, James
  Smith, Andrea Gilardi, Enrico Spinielli, Anthony North, Martin
  Machyna, Marcin Kalicinski, Eli Pousson
* [pins](https://github.com/rstudio/pins-r) ⭐ 335 | 🐛 44 | 🌐 R | 📅 2026-08-02 by Julia Silge, Hadley
  Wickham, Javier Luraschi, Posit Software, PBC
* [widyr](https://github.com/juliasilge/widyr) ⭐ 333 | 🐛 18 | 🌐 R | 📅 2026-03-09 by David Robinson,
  Kanishka Misra, Julia Silge
* [canvasXpress](https://github.com/neuhausi/canvasXpress) ⭐ 313 | 🐛 27 | 🌐 R | 📅 2026-08-21 by Isaac
  Neuhaus, Connie Brett
* [gapminder](https://github.com/jennybc/gapminder) ⭐ 305 | 🐛 0 | 🌐 R | 📅 2025-06-12 by Jennifer Bryan
* [SuperLearner](https://github.com/ecpolley/SuperLearner) ⭐ 294 | 🐛 20 | 🌐 R | 📅 2026-08-16 by Eric
  Polley, Erin LeDell, Chris Kennedy, Sam Lendle, Mark van der Laan
* [googleAnalyticsR](https://github.com/8-bit-sheep/googleAnalyticsR/) ⭐ 274 | 🐛 33 | 🌐 HTML | 📅 2024-09-05
  by Mark Edmondson, Erik Grönroos, Artem Klevtsov, Johann deBoer, David
  Watkins, Olivia Brode-Roger, Jas Sohi, Zoran Selinger, Octavian
  Corlade, Maegan Whytock, Masaki Terashi
* [ggseg](https://github.com/ggsegverse/ggseg) ⭐ 270 | 🐛 2 | 🌐 R | 📅 2026-08-10 by Athanasia Mo
  Mowinckel, Didac Vidal-Piñeiro, Ramiro Magno, Center for Lifespan
  Changes in Brain and Cognition, University of Oslo, Norway
* [tsfeatures](https://github.com/robjhyndman/tsfeatures) ⭐ 262 | 🐛 2 | 🌐 R | 📅 2026-06-30 by Rob
  Hyndman, Yanfei Kang, Pablo Montero-Manso, Mitchell O’Hara-Wild,
  Thiyanga Talagala, Earo Wang, Yangzhuoran Yang, Souhaib Ben Taieb, Cao
  Hanqing, D K Lake, Nikolay Laptev, J R Moorman, Bohan Zhang
* [openintro](https://github.com/OpenIntroStat/openintro/) ⭐ 256 | 🐛 3 | 🌐 R | 📅 2026-08-19 by Mine
  Çetinkaya-Rundel, David Diez, Andrew Bray, Albert Y. Kim, Ben Baumer,
  Chester Ismay, Nick Paterno, Christopher Barr
* [gmailr](https://github.com/r-lib/gmailr) ⭐ 237 | 🐛 23 | 🌐 R | 📅 2026-01-30 by Jim Hester, Jennifer
  Bryan, Posit Software, PBC
* [qualtRics](https://github.com/ropensci/qualtRics) ⭐ 229 | 🐛 49 | 🌐 R | 📅 2026-06-25 by Jasper Ginn,
  Jackson Curtis, Shaun Jackson, Samuel Kaminsky, Eric Knudsen, Joseph
  O’Brien, Daniel Seneca, Julia Silge, Phoebe Wong
* [edibble](https://github.com/emitanaka/edibble) ⭐ 221 | 🐛 12 | 🌐 R | 📅 2025-03-30 by Emi Tanaka
* [workflows](https://github.com/tidymodels/workflows) ⭐ 211 | 🐛 18 | 🌐 R | 📅 2025-11-14 by Davis Vaughan,
  Simon Couch, Hannah Frick, Posit Software, PBC
* [memer](https://github.com/sctyner/memer) ⭐ 204 | 🐛 5 | 🌐 R | 📅 2021-08-05 by Sam Tyner, Haley Jeppson
* [vetiver](https://github.com/rstudio/vetiver-r/) ⭐ 199 | 🐛 29 | 🌐 R | 📅 2026-08-23 by Julia Silge, Posit
  Software, PBC
* [nimble](https://github.com/nimble-dev/nimble) ⭐ 197 | 🐛 98 | 🌐 C++ | 📅 2026-08-21 by Perry de Valpine,
  Christopher Paciorek, Daniel Turek, Nick Michaud, Cliff
  Anderson-Bergman, Fritz Obermeyer, Claudia Wehrhahn Cortes, Abel
  Rodríguez, Duncan Temple Lang, Wei Zhang, Sally Paganin, Joshua Hug,
  Paul van Dam-Bates, Jagadish Babu, Lauren Ponisio, Peter Sujan
* [flametree](https://github.com/djnavarro/flametree) ⭐ 170 | 🐛 0 | 🌐 R | 📅 2026-07-28 by Danielle
  Navarro
* [dataspice](https://github.com/ropensci/dataspice) ⭐ 163 | 🐛 34 | 🌐 R | 📅 2025-09-24 by Carl Boettiger,
  Scott Chamberlain, Auriel Fournier, Kelly Hondula, Anna Krystalli,
  Bryce Mecum, Maëlle Salmon, Kate Webbink, Kara Woo, Irene Steves
* [messy](https://github.com/nrennie/messy) ⭐ 156 | 🐛 2 | 🌐 R | 📅 2025-08-29 by Nicola Rennie
* [ghclass](https://github.com/rundel/ghclass) ⭐ 147 | 🐛 20 | 🌐 R | 📅 2026-08-20 by Colin Rundel, Mine
  Cetinkaya-Rundel, Therese Anders
* [dataMaid](https://github.com/ekstroem/dataMaid) ⭐ 143 | 🐛 15 | 🌐 HTML | 📅 2025-04-13 by Anne Helby
  Petersen, Claus Thorn Ekstrøm
* [changepoint](https://github.com/rkillick/changepoint/) ⭐ 141 | 🐛 14 | 🌐 R | 📅 2026-08-08 by Rebecca
  Killick, Kaylea Haynes, Harjit Hullait, Idris Eckley, Paul Fearnhead,
  Robin Long, Jamie Lee
* [butcher](https://github.com/tidymodels/butcher) ⭐ 139 | 🐛 12 | 🌐 R | 📅 2026-02-25 by Joyce Cahoon,
  Davis Vaughan, Max Kuhn, Alex Hayes, Julia Silge, Posit Software, PBC
* [repurrrsive](https://github.com/jennybc/repurrrsive) ⭐ 139 | 🐛 5 | 🌐 R | 📅 2023-08-08 by Jennifer
  Bryan, Charlotte Wickham, Posit Software, PBC
* [projmgr](https://github.com/emilyriederer/projmgr) ⭐ 126 | 🐛 7 | 🌐 R | 📅 2025-11-29 by Emily Riederer
* [censored](https://github.com/tidymodels/censored) ⭐ 125 | 🐛 28 | 🌐 R | 📅 2026-08-21 by Emil Hvitfeldt,
  Hannah Frick, Posit Software, PBC
* [anicon](https://github.com/emitanaka/anicon) ⭐ 123 | 🐛 4 | 🌐 R | 📅 2026-07-13 by Emi Tanaka
* [shinyLP](https://github.com/jasdumas/shinyLP) ⭐ 119 | 🐛 0 | 🌐 R | 📅 2025-05-15 by Jasmine Daly
* [weathercan](https://github.com/ropensci/weathercan/) ⭐ 117 | 🐛 7 | 🌐 R | 📅 2026-08-17 by Steffi
  LaZerte, Sam Albers, Nick Brown, Kevin Cazelles, Richard Littauer,
  Shandiya Balasubramaniam, Mark Ciechanowski, Jeremy Selva, Kelli F.
  Johnson, Russ Allen, Everett Snieder, Josh Persi, Mahjabin Oyshi
* [dials](https://github.com/tidymodels/dials) ⭐ 116 | 🐛 19 | 🌐 R | 📅 2026-08-13 by Max Kuhn, Hannah
  Frick, Posit Software, PBC
* [gargle](https://github.com/r-lib/gargle) ⭐ 113 | 🐛 34 | 🌐 R | 📅 2026-05-28 by Jennifer Bryan, Craig
  Citro, Hadley Wickham, Google Inc, Posit Software, PBC
* [jasmines](https://github.com/djnavarro/jasmines) ⭐ 113 | 🐛 8 | 🌐 R | 📅 2021-12-14 by Danielle Navarro
* [pkgsearch](https://github.com/r-hub/pkgsearch) ⭐ 111 | 🐛 31 | 🌐 R | 📅 2025-04-12 by Gábor Csárdi,
  Maëlle Salmon, R Consortium
* [hardhat](https://github.com/tidymodels/hardhat) ⭐ 108 | 🐛 6 | 🌐 R | 📅 2026-06-09 by Hannah Frick,
  Davis Vaughan, Max Kuhn, Posit Software, PBC
* [Metrics](https://github.com/mfrasco/Metrics) ⭐ 102 | 🐛 20 | 🌐 R | 📅 2019-10-25 by Ben Hamner, Michael
  Frasco, Erin LeDell
* [tidylo](https://github.com/juliasilge/tidylo) ⭐ 98 | 🐛 0 | 🌐 R | 📅 2022-03-22 by Tyler Schnoebelen,
  Julia Silge, Alex Hayes
* [janeaustenr](https://github.com/juliasilge/janeaustenr) ⭐ 97 | 🐛 1 | 🌐 R | 📅 2022-08-26 by Julia
  Silge
* [workflowsets](https://github.com/tidymodels/workflowsets) ⭐ 97 | 🐛 14 | 🌐 R | 📅 2026-02-24 by Hannah
  Frick, Max Kuhn, Simon Couch, Posit Software, PBC
* [namer](https://github.com/jumpingrivers/namer) ⭐ 96 | 🐛 4 | 🌐 R | 📅 2025-01-23 by Colin Gillespie,
  Steph Locke, Maëlle Salmon, Ellis Valentiner, Charlie Hadley, Jumping
  Rivers, Han Oostdijk, Patrick Schratz
* [vcr](https://github.com/ropensci/vcr/) ⭐ 96 | 🐛 34 | 🌐 R | 📅 2026-08-18 by Scott Chamberlain, Aaron
  Wolen, Maëlle Salmon, Daniel Possenriede, Hadley Wickham, rOpenSci
* [geomnet](https://github.com/sctyner/geomnet) ⭐ 94 | 🐛 10 | 🌐 R | 📅 2021-08-23 by Sam Tyner, Heike
  Hofmann, Nicholas Tierney
* [trackeR](https://github.com/trackerproject/trackeR) ⭐ 92 | 🐛 7 | 🌐 HTML | 📅 2025-08-29 by Ioannis
  Kosmidis, Hannah Frick, Robin Hornak
* [ggflowchart](https://github.com/nrennie/ggflowchart) ⭐ 90 | 🐛 11 | 🌐 R | 📅 2023-12-20 by Nicola Rennie
* [monochromeR](https://github.com/cararthompson/monochromeR) ⭐ 89 | 🐛 3 | 🌐 R | 📅 2025-09-10 by Cara
  Thompson
* [opencage](https://github.com/ropensci/opencage) ⭐ 89 | 🐛 5 | 🌐 R | 📅 2025-01-25 by Daniel
  Possenriede, Jesse Sadler, Maëlle Salmon, Noam Ross, Jake Russ, Julia
  Silge
* [cransays](https://github.com/r-hub/cransays) ⭐ 83 | 🐛 9 | 🌐 R | 📅 2026-08-23 by Hugo Gruson, Maëlle
  Salmon, Locke Data, Stephanie Locke, Mitchell O’Hara-Wild, Lluís
  Revilla Sancho, Jim Hester, Hadley Wickham
* [meetupr](https://github.com/rladies/meetupr) ⭐ 80 | 🐛 6 | 🌐 R | 📅 2026-05-14 by Athanasia Mo
  Mowinckel, Erin LeDell, Olga Mierzwa-Sulima, Lucy D’Agostino McGowan,
  Claudia Vitolo, Gabriela De Queiroz, Michael Beigelmacher, Augustina
  Ragwitz, Greg Sutcliffe, Rick Pack, Ben Ubah, Maëlle Salmon, Barret
  Schloerke, RLadies+
* [spatialsample](https://github.com/tidymodels/spatialsample) ⭐ 80 | 🐛 4 | 🌐 R | 📅 2026-07-06 by
  Michael Mahoney, Julia Silge, Posit Software, PBC
* [seer](https://github.com/thiyangt/seer) ⭐ 78 | 🐛 0 | 🌐 R | 📅 2022-10-01 by Thiyanga Talagala, Rob J
  Hyndman, George Athanasopoulos
* [bayesrules](https://github.com/bayes-rules/bayesrules/) ⭐ 74 | 🐛 7 | 🌐 R | 📅 2026-01-20 by Mine
  Dogucu, Alicia Johnson, Miles Ott
* [multilevelmod](https://github.com/tidymodels/multilevelmod) ⭐ 74 | 🐛 22 | 🌐 R | 📅 2026-04-14 by Max
  Kuhn, Hannah Frick, RStudio
* [statsr](https://github.com/StatsWithR/statsr) ⭐ 73 | 🐛 6 | 🌐 R | 📅 2021-01-27 by Colin Rundel, Mine
  Cetinkaya-Rundel, Merlise Clyde, David Banks
* [bakeoff](https://github.com/apreshill/bakeoff) ⭐ 70 | 🐛 5 | 🌐 R | 📅 2022-11-02 by Alison Hill,
  Chester Ismay, Richard Iannone
* [DALEXtra](https://github.com/ModelOriented/DALEXtra) ⭐ 68 | 🐛 3 | 🌐 R | 📅 2026-01-14 by Szymon
  Maksymiuk, Przemyslaw Biecek, Hubert Baniecki, Anna Kozak
* [USAboundaries](https://github.com/ropensci/USAboundaries) ⭐ 68 | 🐛 0 | 🌐 R | 📅 2026-01-29 by Lincoln
  Mullen, Jordan Bratt, United States Census Bureau, Jacci Ziebert
* [codemetar](https://github.com/ropensci/codemetar) ⭐ 67 | 🐛 26 | 🌐 R | 📅 2026-02-10 by Carl Boettiger,
  Anna Krystalli, Toph Allen, Maëlle Salmon, rOpenSci, Katrin Leinweber,
  Noam Ross, Arfon Smith, Jeroen Ooms, Sebastian Meyer, Michael Rustler,
  Hauke Sonnenberg, Sebastian Kreutzer, Thierry Onkelinx
* [tourr](https://github.com/ggobi/tourr) ⭐ 67 | 🐛 1 | 🌐 R | 📅 2026-07-30 by Hadley Wickham, Dianne
  Cook, Nick Spyrison, Ursula Laa, H. Sherry Zhang, Stuart Lee
* [ggseg.extra](https://github.com/ggsegverse/ggseg.extra) ⭐ 66 | 🐛 22 | 🌐 R | 📅 2026-08-22 by Athanasia
  Mo Mowinckel, Didac Vidal-Piñeiro, John Muschelli
* [oddstream](https://github.com/pridiltal/oddstream) ⭐ 64 | 🐛 2 | 🌐 R | 📅 2020-04-02 by Priyanga Dilini
  Talagala, Rob J. Hyndman, Kate Smith-Miles
* [tinkr](https://github.com/ropensci/tinkr) ⭐ 62 | 🐛 35 | 🌐 R | 📅 2026-06-01 by Maëlle Salmon, Zhian N.
  Kamvar, Jeroen Ooms, Nick Wellnhofer, rOpenSci, Peter Daengeli
* [Vizumap](https://github.com/lydialucchesi/Vizumap) ⭐ 61 | 🐛 0 | 🌐 R | 📅 2025-06-23 by Lydia Lucchesi,
  Petra Kuhnert, Christopher Wikle, Benedict
* [auditor](https://github.com/ModelOriented/auditor) ⭐ 60 | 🐛 8 | 🌐 R | 📅 2024-01-09 by Alicja
  Gosiewska, Przemyslaw Biecek, Hubert Baniecki, Tomasz Mikołajczyk,
  Michal Burdukiewicz, Szymon Maksymiuk
* [stray](https://github.com/pridiltal/stray) ⭐ 59 | 🐛 2 | 🌐 R | 📅 2023-11-19 by Priyanga Dilini
  Talagala, Rob J Hyndman, Kate Smith-Miles
* [FactoMineR](https://github.com/husson/FactoMineR) ⭐ 58 | 🐛 26 | 🌐 HTML | 📅 2026-07-02 by Francois Husson,
  Julie Josse, Sebastien Le, Jeremy Mazet
* [cubble](https://github.com/huizezhang-sherry/cubble) ⭐ 57 | 🐛 4 | 🌐 R | 📅 2024-10-05 by H. Sherry
  Zhang, Dianne Cook, Ursula Laa, Nicolas Langrené, Patricia Menéndez
* [MLDataR](https://github.com/StatsGary/MLDataR) ⭐ 55 | 🐛 0 | 🌐 R | 📅 2023-11-23 by Gary Hutson, Asif
  Laldin, Isabella Velásquez
* [connectapi](https://github.com/posit-dev/connectapi) ⭐ 54 | 🐛 77 | 🌐 R | 📅 2026-05-05 by Kara Woo,
  Toph Allen, Neal Richardson, Sean Lopp, Cole Arendt, Posit, PBC
* [overviewR](https://github.com/cosimameyer/overviewR) ⭐ 54 | 🐛 1 | 🌐 R | 📅 2026-05-04 by Cosima Meyer,
  Dennis Hammerschmidt
* [PrettyCols](https://github.com/nrennie/PrettyCols) ⭐ 54 | 🐛 1 | 🌐 R | 📅 2025-04-23 by Nicola Rennie
* [cellranger](https://github.com/rsheets/cellranger) ⭐ 52 | 🐛 21 | 🌐 R | 📅 2023-02-17 by Jennifer Bryan,
  Hadley Wickham
* [glitter](https://github.com/lvaudor/glitter) ⭐ 52 | 🐛 54 | 🌐 Rez | 📅 2024-07-10 by Lise Vaudor, Maëlle
  Salmon
* [dados](https://github.com/cienciadedatos/dados) ⭐ 50 | 🐛 9 | 🌐 R | 📅 2026-08-19 by Riva Quiroga, Sara
  Mortara, Beatriz Milz, Andrea Sánchez-Tapia, Alejandra Andrea Tapia
  Silva, Beatriz Maurer Costa, Jean Prado, Renata Hirota, William
  Amorim, Emmanuelle Rodrigues Nunes
* [modleR](https://github.com/Model-R/modleR) ⭐ 50 | 🐛 22 | 🌐 R | 📅 2025-08-09 by Andrea Sánchez-Tapia,
  Sara Mortara, Diogo Rocha, Felipe Barros, Guilherme Gall, Tiago Castro
  Silva
* [PKPDsim](https://github.com/InsightRX/PKPDsim) ⭐ 50 | 🐛 4 | 🌐 R | 📅 2026-08-20 by Ron Keizer, Jasmine
  Hughes, Dominic Tong, Kara Woo, Jordan Brooks, InsightRX
* [qtwAcademic](https://github.com/andreaczhang/qtwAcademic) ⭐ 50 | 🐛 1 | 🌐 R | 📅 2023-01-12 by Chi
  Zhang
* [shinymodels](https://github.com/tidymodels/shinymodels) ⭐ 50 | 🐛 5 | 🌐 R | 📅 2025-10-22 by Max Kuhn,
  Shisham Adhikari, Julia Silge, Simon Couch, Posit Software, PBC
* [datos](https://github.com/cienciadedatos/datos) ⭐ 48 | 🐛 3 | 🌐 R | 📅 2026-01-29 by Riva Quiroga,
  Edgar Ruiz, Mauricio Vargas, Mauro Lepore, Rayna Harris, Daniela
  Vasquez, Joshua Kunst
* [riem](https://github.com/ropensci/riem) ⭐ 47 | 🐛 4 | 🌐 R | 📅 2025-10-21 by Maëlle Salmon, Brooke
  Anderson, CHAI Project, rOpenSci, Daryl Herzmann, Jonathan Elchison
* [datalegreyar](https://github.com/emitanaka/datalegreyar) ⭐ 45 | 🐛 0 | 🌐 R | 📅 2018-07-16 by Emi
  Tanaka
* [ggseg3d](https://github.com/ggsegverse/ggseg3d) ⭐ 45 | 🐛 8 | 🌐 R | 📅 2026-08-07 by Athanasia Mo
  Mowinckel, Didac Vidal-Piñeiro, Center for Lifespan Changes in Brain
  and Cognition, University of Oslo, three.js authors
* [subsemble](https://github.com/ledell/subsemble) ⭐ 43 | 🐛 1 | 🌐 R | 📅 2022-01-21 by Erin LeDell,
  Stephanie Sapp, Mark van der Laan
* [gtreg](https://github.com/shannonpileggi/gtreg) ⭐ 42 | 🐛 7 | 🌐 R | 📅 2025-12-01 by Shannon Pileggi,
  Daniel D. Sjoberg
* [ggPMX](https://github.com/ggPMXdevelopment/ggPMX) ⭐ 40 | 🐛 61 | 🌐 R | 📅 2026-07-01 by Amine Gassem,
  Bruno Bieth, Irina Baltcheva, Thomas Dumortier, Christian Bartels,
  Souvik Bhattacharya, Inga Ludwig, Ines Paule, Didier Renard, Matthew
  Fidler, Seid Hamzic, Benjamin Guiastrennec, Kyle T Baron, Qing Xi Ooi,
  Aleksandr Pogodaev, Danielle Navarro, Ibtissem Rebai, Mahmoud Ali,
  Novartis Pharma AG
* [rHealthDataGov](https://github.com/rOpenHealth/rHealthDataGov) ⭐ 40 | 🐛 2 | 🌐 R | 📅 2014-12-29 by
  Erin LeDell
* [rjtools](https://github.com/rjournal/rjtools) ⭐ 39 | 🐛 43 | 🌐 HTML | 📅 2026-07-20 by Mitchell
  O’Hara-Wild, Stephanie Kobakian, H. Sherry Zhang, Di Cook, Simon
  Urbanek, Christophe Dervieux, R Journal Technical Editor
* [sknifedatar](https://github.com/rafzamb/sknifedatar) ⭐ 38 | 🐛 5 | 🌐 R | 📅 2023-02-06 by Rafael
  Zambrano, Karina Bartolome, Rodrigo Serrano
* [ggauto](https://github.com/nrennie/ggauto) ⭐ 37 | 🐛 4 | 🌐 R | 📅 2026-06-28 by Nicola Rennie
* [scDD](https://github.com/kdkorthauer/scDD) ⭐ 35 | 🐛 0 | 🌐 R | 📅 2022-03-24 by Keegan Korthauer
* [verbaliseR](https://github.com/cararthompson/verbaliseR) ⭐ 33 | 🐛 0 | 🌐 R | 📅 2022-10-04 by Cara
  Thompson
* [clinPK](https://github.com/InsightRX/clinPK) ⭐ 32 | 🐛 0 | 🌐 R | 📅 2026-07-31 by Ron Keizer, Jasmine
  Hughes, Dominic Tong, Kara Woo, InsightRX
* [RCMIP5](https://github.com/ktoddbrown/RCMIP5) ⚠️ Archived by Ben Bond-Lamberty,
  Kathe Todd-Brown
* [bundle](https://github.com/rstudio/bundle) ⭐ 31 | 🐛 7 | 🌐 R | 📅 2025-12-10 by Julia Silge, Simon
  Couch, Qiushi Yan, Max Kuhn, Posit Software, PBC
* [redcapAPI](https://github.com/vubiostat/redcapAPI) ⭐ 31 | 🐛 18 | 🌐 R | 📅 2026-08-12 by Benjamin
  Nutter, Shawn Garbett, Savannah Obregon, Thomas Obadia, Marcus Lehr,
  Brian High, Stephen Lane, Will Beasley, Will Gray, Nick Kennedy, Tan
  Hsi-Nien, Jeffrey Horner, Jeremy Stephens, Cole Beck, Bradley Johnson,
  Philip Chase, Paddy Tobias, Michael Chirico, William Sharp, Alexander
  Strübing
* [vcdExtra](https://github.com/friendly/vcdExtra) ⭐ 28 | 🐛 5 | 🌐 HTML | 📅 2026-08-22 by Michael Friendly,
  David Meyer, Achim Zeileis, Duncan Murdoch, Heather Turner, David
  Firth, Daniel Sabanes Bove, Matt Kumar, Shuguang Sun, Gavin Klorfine
* [PlackettLuce](https://github.com/hturner/PlackettLuce) ⭐ 27 | 🐛 6 | 🌐 HTML | 📅 2026-03-24 by Heather
  Turner, Ioannis Kosmidis, David Firth, Jacob van Etten
* [cereal](https://github.com/r-lib/cereal/) ⭐ 26 | 🐛 1 | 🌐 R | 📅 2025-10-20 by Julia Silge, Davis
  Vaughan, Posit Software, PBC
* [quartose](https://github.com/djnavarro/quartose) ⭐ 26 | 🐛 0 | 🌐 R | 📅 2026-08-06 by Danielle Navarro
* [BradleyTerry2](https://github.com/hturner/BradleyTerry2) ⭐ 25 | 🐛 18 | 🌐 R | 📅 2025-04-10 by Heather
  Turner, David Firth
* [cvAUC](https://github.com/ledell/cvAUC) ⭐ 25 | 🐛 7 | 🌐 R | 📅 2022-01-18 by Erin LeDell, Maya
  Petersen, Mark van der Laan
* [ttbbeer](https://github.com/jasdumas/ttbbeer) ⭐ 25 | 🐛 0 | 🌐 R | 📅 2025-06-30 by Jasmine Daly
* [BradleyTerryScalable](https://github.com/EllaKaye/BradleyTerryScalable) ⭐ 24 | 🐛 3 | 🌐 R | 📅 2022-09-28
  by Ella Kaye, David Firth
* [poissonreg](https://github.com/tidymodels/poissonreg) ⭐ 23 | 🐛 4 | 🌐 R | 📅 2026-04-20 by Max Kuhn,
  Hannah Frick, Posit Software, PBC
* [tableHTML](https://github.com/LyzandeR/tableHTML) ⭐ 20 | 🐛 10 | 🌐 R | 📅 2025-11-28 by Theo Boutaris,
  Clemens Zauchner, Dana Jomar
* [ukbabynames](https://github.com/mine-cetinkaya-rundel/ukbabynames) ⭐ 20 | 🐛 0 | 🌐 R | 📅 2022-03-25 by
  Mine Çetinkaya-Rundel, Thomas J. Leeper, Nicholas Goguen-Compagnoni,
  Sara Lemus
* [agroclimatico](https://github.com/ropensci/agroclimatico) ⭐ 19 | 🐛 4 | 🌐 C++ | 📅 2025-05-05 by Yanina
  Bellini Saibene, Elio Campitelli, Paola Corrales, Natalia Gattinoni,
  Ruida Zhong, Verónica Cruz-Alonso, Priscilla Minotti
* [AnnotationHub](https://github.com/Bioconductor/AnnotationHub) ⭐ 19 | 🐛 11 | 🌐 R | 📅 2026-06-30 by
  Bioconductor Package Maintainer, Martin Morgan, Marc Carlson, Dan
  Tenenbaum, Sonali Arora, Valerie Oberchain, Kayla Morrell, Lori
  Shepherd
* [colorhex](https://github.com/drmowinckels/colorhex) ⭐ 19 | 🐛 0 | 🌐 R | 📅 2025-07-22 by Athanasia Mo
  Mowinckel, Julia Romanowska
* [ech](https://github.com/calcita/ech) ⭐ 19 | 🐛 2 | 🌐 R | 📅 2024-02-27 by Gabriela Mathieu, Richard
  Detomasi, Tati Micheletti
* [mortAAR](https://github.com/ISAAKiel/mortAAR) ⭐ 19 | 🐛 3 | 🌐 R | 📅 2026-05-02 by Nils
  Mueller-Scheessel, Martin Hinz, Clemens Schmid, Christoph Rinne,
  Daniel Knitter, Wolfgang Hamer, Dirk Seidensticker, Franziska Faupel,
  Carolin Tietze, Nicole Grunert
* [vagalumeR](https://github.com/r-music/vagalumeR) ⭐ 19 | 🐛 0 | 🌐 R | 📅 2019-06-07 by Bruna Wundervald
* [GWASTools](https://github.com/smgogarten/GWASTools) ⭐ 18 | 🐛 2 | 🌐 R | 📅 2025-03-18 by Stephanie M.
  Gogarten, Cathy Laurie, Tushar Bhangale, Matthew P. Conomos, Cecelia
  Laurie, Michael Lawrence, Caitlin McHugh, Ian Painter, Xiuwen Zheng,
  Jess Shen, Rohit Swarnkar, Adrienne Stilp, Sarah Nelson, David Levine,
  Sonali Kumari, Stephanie M. Gogarten
* [methylCC](https://github.com/stephaniehicks/methylCC/) ⭐ 18 | 🐛 0 | 🌐 R | 📅 2025-11-26 by
  Stephanie C. Hicks, Rafael Irizarry
* [odbr](https://github.com/hsvab/odbr) ⭐ 18 | 🐛 7 | 🌐 R | 📅 2025-03-02 by Haydee Svab, Beatriz Milz,
  Diego Rabatone Oliveira, Rafael H. M. Pereira
* [PPforest](https://github.com/natydasilva/PPforest) ⭐ 18 | 🐛 1 | 🌐 C++ | 📅 2025-09-04 by Natalia da
  Silva, Dianne Cook, Eun-Kyung Lee
* [wingen](https://github.com/AnushaPB/wingen) ⭐ 18 | 🐛 0 | 🌐 R | 📅 2026-04-28 by Anusha Bishop, Anne
  Chambers, Ian Wang
* [gnm](https://github.com/hturner/gnm) ⭐ 17 | 🐛 15 | 🌐 R | 📅 2024-03-20 by Heather Turner, David Firth,
  Brian Ripley, Bill Venables, Douglas M. Bates, Martin Maechler
* [naturecounts](https://github.com/BirdsCanada/naturecounts) ⭐ 17 | 🐛 12 | 🌐 R | 📅 2026-08-21 by Steffi
  LaZerte, Denis Lepage
* [RSSthemes](https://github.com/nrennie/RSSthemes) ⭐ 17 | 🐛 3 | 🌐 R | 📅 2024-03-02 by Nicola Rennie,
  Royal Statistical Society
* [SOMbrero](https://github.com/tuxette/SOMbrero) ⭐ 17 | 🐛 0 | 📅 2025-08-19 by Nathalie Vialaneix,
  Elise Maigne, Jerome Mariette, Madalina Olteanu, Fabrice Rossi, Laura
  Bendhaiba, Julien Boelaert
* [tailor](https://github.com/tidymodels/tailor) ⭐ 17 | 🐛 15 | 🌐 R | 📅 2025-08-26 by Simon Couch, Hannah
  Frick, Emil HvitFeldt, Max Kuhn, Posit Software, PBC
* [adjclust](https://github.com/pneuvial/adjclust) ⭐ 16 | 🐛 5 | 🌐 R | 📅 2025-11-21 by Christophe
  Ambroise, Shubham Chaturvedi, Alia Dehman, Pierre Neuvial, Guillem
  Rigaill, Nathalie Vialaneix, Gabriel Hoffman
* [prepdat](http://github.com/ayalaallon/prepdat) ⭐ 16 | 🐛 0 | 🌐 R | 📅 2019-03-01 by Ayala S. Allon, Roy
  Luria, James Grange, Nachshon Meiran
* [datelife](https://github.com/phylotastic/datelife) ⭐ 15 | 🐛 55 | 🌐 R | 📅 2025-11-02 by Brian O’Meara,
  Jonathan Eastman, Tracy Heath, April Wright, Klaus Schliep, Scott
  Chamberlain, Peter Midford, Luke Harmon, Joseph Brown, Matt Pennell,
  Mike Alfaro, Luna L. Sanchez Reyes, Emily Jane McTavish
* [quadkeyr](https://github.com/ropensci/quadkeyr) ⭐ 15 | 🐛 3 | 🌐 R | 📅 2025-03-25 by Florencia
  D’Andrea, Pilar Fernandez, Maria Paula Caldas, Vincent van Hees,
  Andrew Pulsipher, CDC’s Center for Forecasting and Outbreak Analytics,
  MIDAS-NIH COVID-19 urgent grant program, Paul G. Allen School for
  Global Health, Washington State University
* [avilistr](https://github.com/dalyanalytics/avilistr) ⭐ 14 | 🐛 0 | 🌐 R | 📅 2025-06-17 by Jasmine Daly,
  AviList Core Team
* [BiocFileCache](https://github.com/Bioconductor/BiocFileCache) ⭐ 14 | 🐛 11 | 🌐 R | 📅 2026-04-29 by Lori
  Shepherd, Martin Morgan
* [sensiPhy](https://github.com/paternogbc/sensiPhy) ⭐ 14 | 🐛 6 | 🌐 R | 📅 2020-06-10 by Gustavo Paterno,
  Gijsbert Werner, Caterina Penone, Pablo Martinez
* [simex](https://github.com/wolfganglederer/simex) ⭐ 14 | 🐛 5 | 🌐 R | 📅 2019-08-06 by Wolfgang Lederer,
  Heidi Seibold, Helmut Küchenhoff, Chris Lawrence, Rasmus Froberg
  Brøndum
* [traudem](https://github.com/lucarraro/traudem) ⭐ 14 | 🐛 2 | 🌐 R | 📅 2024-04-24 by Luca Carraro,
  University of Zurich, Maëlle Salmon, Wael Sadek, Kirill Müller
* [typeR](https://github.com/Fgazzelloni/typeR) ⭐ 14 | 🐛 0 | 🌐 R | 📅 2026-02-08 by Federica Gazzelloni
* [uiothemes](https://github.com/drmowinckels/uiothemes) ⭐ 14 | 🐛 0 | 🌐 HTML | 📅 2023-08-16 by Athanasia Mo
  Mowinckel
* [vivo](https://github.com/ModelOriented/vivo) ⭐ 14 | 🐛 2 | 🌐 R | 📅 2020-09-26 by Anna Kozak,
  Przemyslaw Biecek
* [QueryWikidataR](https://github.com/serenasignorelli/QueryWikidataR) ⭐ 13 | 🐛 1 | 🌐 R | 📅 2017-01-18
  by Serena Signorelli
* [sessioncheck](https://github.com/djnavarro/sessioncheck) ⭐ 13 | 🐛 5 | 🌐 R | 📅 2026-07-29 by Danielle
  Navarro
* [LITAP](https://github.com/FRDC-SHL/LITAP) ⭐ 12 | 🐛 3 | 🌐 R | 📅 2024-10-02 by Steffi LaZerte, Sheng
  Li, Agriculture and Agri-Food Canada
* [lsr](https://github.com/djnavarro/lsr) ⭐ 12 | 🐛 1 | 🌐 R | 📅 2026-07-19 by Danielle Navarro
* [tanggle](https://github.com/KlausVigo/tanggle) ⭐ 12 | 🐛 5 | 🌐 R | 📅 2026-06-11 by Klaus Schliep,
  Marta Vidal-Garcia, Claudia Solis-Lemus, Leann Biancani, Eren Ada, L.
  Francisco Henao Diaz, Guangchuang Yu, Joshua Justison
* [usdata](https://github.com/OpenIntroStat/usdata) ⭐ 12 | 🐛 3 | 🌐 R | 📅 2024-06-02 by Mine
  Çetinkaya-Rundel, David Diez, Leah Dorazio
* [ExperimentHub](https://github.com/Bioconductor/ExperimentHub) ⭐ 11 | 🐛 7 | 🌐 R | 📅 2026-08-19 by
  Bioconductor Package Maintainer, Martin Morgan, Marc Carlson, Dan
  Tenenbaum, Sonali Arora, Valerie Oberchain, Kayla Morrell, Lori
  Shepherd
* [lvm4net](http://github.com/igollini/lvm4net) ⭐ 11 | 🐛 2 | 🌐 R | 📅 2021-12-10 by Isabella Gollini
* [shinymatic](https://github.com/karbartolome/shinymatic) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2022-06-23 by Karina
  Bartolome
* [SparseSignatures](https://github.com/danro9685/SparseSignatures) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2026-04-07 by
  Daniele Ramazzotti, Avantika Lal, Keli Liu, Luca De Sano, Robert
  Tibshirani, Arend Sidow
* [aperol](https://github.com/EllaKaye/aperol) ⭐ 10 | 🐛 1 | 🌐 R | 📅 2025-02-27 by Ella Kaye, Kelly
  Bodwin, Collin Schwantes
* [scShapes](https://github.com/Malindrie/scShapes) ⭐ 9 | 🐛 0 | 🌐 R | 📅 2022-11-08 by Malindrie
  Dharmaratne
* [codemeta](https://github.com/cboettig/codemeta) ⭐ 8 | 🐛 2 | 🌐 R | 📅 2023-11-14 by Carl Boettiger,
  Maëlle Salmon, Katrin Leinweber, Noam Ross, Arfon Smith, Jeroen Ooms,
  Sebastian Meyer, Michael Rustler, Hauke Sonnenberg, Sebastian
  Kreutzer, rOpenSci
* [emodnet.wfs](https://github.com/EMODnet/emodnet.wfs) ⭐ 8 | 🐛 5 | 🌐 R | 📅 2026-04-20 by Joana Beja,
  Anna Krystalli, Salvador Fernández-Bejarano, Thomas J Webb, European
  Marine Observation Data Network, VLIZ, Maëlle Salmon, Alec L.
  Robitaille, Liz Hare, François Michonneau
* [pregnancy](https://github.com/EllaKaye/pregnancy) ⭐ 8 | 🐛 1 | 🌐 R | 📅 2026-01-15 by Ella Kaye
* [worrrd](https://github.com/anthonypileggi/worrrd) ⭐ 8 | 🐛 13 | 🌐 R | 📅 2022-12-21 by Anthony Pileggi,
  Shannon Pileggi
* [aochelpers](https://github.com/EllaKaye/aochelpers) ⭐ 7 | 🐛 6 | 🌐 R | 📅 2024-11-25 by Ella Kaye
* [artpack](https://github.com/Meghansaha/artpack) ⭐ 7 | 🐛 8 | 🌐 R | 📅 2025-09-17 by Meghan Harris
* [mitey](https://github.com/kylieainslie/mitey) ⭐ 7 | 🐛 9 | 🌐 TeX | 📅 2026-08-19 by Kylie Ainslie
* [ShapeRotator](https://github.com/marta-vidalgarcia/ShapeRotator) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2021-02-05 by
  Marta Vidal-Garcia, Lashi Bandara, J. Scott Keogh
* [SISINTAR](https://github.com/inta-suelos/SISINTAR) ⭐ 7 | 🐛 4 | 🌐 R | 📅 2023-05-30 by Yanina Bellini
  Saibene, Elio Campitelli, Paola Corrales
* [arttools](https://github.com/djnavarro/arttools) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2026-07-19 by Danielle Navarro
* [basepenguins](https://github.com/EllaKaye/basepenguins) ⭐ 6 | 🐛 5 | 🌐 R | 📅 2025-04-10 by Ella Kaye,
  Heather Turner, Achim Zeileis
* [cherryblossom](https://github.com/OpenIntroStat/cherryblossom) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2024-01-10 by
  Mine Çetinkaya-Rundel
* [dySEM](https://github.com/jsakaluk/dySEM) ⭐ 6 | 🐛 29 | 🌐 HTML | 📅 2026-05-25 by John Sakaluk, Omar
  Camanto, Christopher Quinn-Nilas, Merissa Prine, Robyn Kilshaw,
  Alexandra Fisher
* [ferrn](https://github.com/huizezhang-sherry/ferrn/) ⭐ 6 | 🐛 1 | 🌐 R | 📅 2025-11-20 by H. Sherry
  Zhang, Dianne Cook, Ursula Laa, Nicolas Langrené, Patricia Menéndez
* [forested](https://github.com/simonpcouch/forested) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2026-08-10 by Grayson White,
  Hannah Frick, Simon Couch, Posit Software, PBC
* [neuromapr](https://github.com/lcbc-uio/neuromapr) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2026-04-30 by Athanasia Mo
  Mowinckel
* [NMAoutlier](https://github.com/petropouloumaria/NMAoutlier) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2025-09-12 by Maria
  Petropoulou, Guido Schwarzer, Agapios Panos, Dimitris Mavridis
* [queue](https://github.com/djnavarro/queue) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2026-07-19 by Danielle Navarro
* [TidyTuesdayAltText](https://github.com/spcanelon/TidyTuesdayAltText) ⭐ 6 | 🐛 2 | 🌐 R | 📅 2022-08-09
  by Silvia Canelón, Thomas Mock, Elizabeth Hare
* [covid19tunisia](https://github.com/MounaBelaid/covid19tunisia) ⭐ 5 | 🐛 2 | 🌐 R | 📅 2020-11-30 by
  Mouna Belaid
* [EpiGenR](https://github.com/lucymli/EpiGenR) ⭐ 5 | 🐛 0 | 🌐 R | 📅 2020-08-19 by Lucy M Li
* [mmaqshiny](https://github.com/meenakshi-kushwaha/mmaqshiny) ⭐ 5 | 🐛 1 | 🌐 R | 📅 2022-05-10 by
  Adithi R. Upadhya, Pratyush Agrawal, Sreekanth Vakacherla, Meenakshi
  Kushwaha
* [roblog](https://github.com/ropenscilabs/roblog) ⭐ 5 | 🐛 4 | 🌐 R | 📅 2026-02-18 by Maëlle Salmon,
  Stefanie Butland, rOpenSci, Amanda Dobbyn, Christophe Dervieux, Romain
  LESUR
* [rstanemax](https://github.com/yoshidk6/rstanemax) ⭐ 5 | 🐛 22 | 🌐 R | 📅 2026-06-13 by Kenta Yoshida,
  Danielle Navarro, Trustees of Columbia University
* [siga](https://github.com/AgRoMeteorologiaINTA/siga) ⭐ 5 | 🐛 2 | 🌐 R | 📅 2024-05-21 by Yanina Bellini
  Saibene, Elio Campitelli, Paola Corrales, Natalia Gattinoni, INTA
* [TutorialgRaficosFN](https://github.com/yabellini/TutorialgRaficosFN) ⭐ 5 | 🐛 0 | 🌐 CSS | 📅 2021-05-11
  by Yanina Bellini Saibene, Yanina Bellini Saibene
* [votesmart](https://github.com/decktools/votesmart/) ⭐ 5 | 🐛 1 | 🌐 R | 📅 2023-05-01 by Deck
  Technologies, Amanda Dobbyn, Max Wood, Alyssa Frazee
* [vultureUtils](https://github.com/kaijagahm/vultureUtils) ⭐ 5 | 🐛 17 | 🌐 R | 📅 2026-01-16 by Kaija
  Gahm
* [bcaquiferdata](https://github.com/bcgov/bcaquiferdata) ⭐ 4 | 🐛 4 | 🌐 R | 📅 2026-05-25 by Steffi
  LaZerte, Christine Bieber, Province of British Columbia
* [ebdbNet](https://github.com/andreamrau/ebdbNet) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2023-09-04 by Andrea Rau
* [hmsidwR](https://github.com/Fgazzelloni/hmsidwR) ⭐ 4 | 🐛 1 | 🌐 R | 📅 2025-05-16 by Federica
  Gazzelloni
* [Kmisc](https://github.com/sysilviakim/Kmisc) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2026-02-18 by Seo-young Silvia Kim
* [logmult](https://github.com/nalimilan/logmult) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2025-08-26 by Milan
  Bouchet-Valat, Heather Turner, Michael Friendly, Jim Lemon, Gabor
  Csardi
* [oregonfrogs](https://github.com/fgazzelloni/oregonfrogs) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2024-11-27 by Federica
  Gazzelloni
* [psidread](https://github.com/Qcrates/psidread) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2026-06-20 by Shuyi Qiu
* [shinyfa](https://github.com/dalyanalytics/shinyfa) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2025-11-10 by Jasmine Daly
* [airports](https://github.com/OpenIntroStat/airports) ⭐ 3 | 🐛 2 | 🌐 R | 📅 2024-01-10 by Mine
  Çetinkaya-Rundel
* [bcgwlreports](https://github.com/bcgov/bcgwlreports) ⭐ 3 | 🐛 1 | 🌐 R | 📅 2024-08-07 by Steffi
  LaZerte, Jon Goetz
* [EPACmodel](https://github.com/phac-modelling-hub/EPACmodel) ⭐ 3 | 🐛 18 | 🌐 R | 📅 2026-02-03 by Irena
  Papst, Michael WZ Li
* [hellodatascience](https://github.com/hellodata-science/hellodatascience) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2026-06-12
  by Mine Dogucu, Catalina Medina, Alma Castro
* [missMDA](https://github.com/husson/missMDA) ⭐ 3 | 🐛 2 | 🌐 R | 📅 2026-06-29 by Francois Husson, Julie
  Josse
* [parmsurvfit](https://github.com/apjacobson/parmsurvfit) ⭐ 3 | 🐛 4 | 🌐 R | 📅 2018-12-07 by Ashley
  Jacobson, Victor Wilson, Shannon Pileggi
* [tidyquintro](https://github.com/drmowinckels/tidyquintro) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2023-08-23 by
  Athanasia Mo Mowinckel
* [USCensus2020](https://github.com/shreshtha48/USCensus2020) ⭐ 3 | 🐛 2 | 🌐 R | 📅 2024-04-26 by
  shreshtha modi
* [washi](https://github.com/WA-Department-of-Agriculture/washi) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2025-09-16 by
  Jadey Ryan, Molly McIlquham, Dani Gelardi, Washington State Department
  of Agriculture
* [bootLong](https://github.com/PratheepaJ/bootLong) ⭐ 2 | 🐛 1 | 🌐 R | 📅 2020-04-02 by Jeganathan
  Pratheepa, Holmes, Susan
* [dobtools](https://github.com/aedobbyn/dobtools) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2019-05-03 by Amanda Dobbyn
* [forwards](https://github.com/forwards/forwards) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2023-12-08 by Heather Turner,
  Oliver Keyes
* [implicitMeasures](https://github.com/OttaviaE/implicitMeasures) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2026-08-06 by
  Ottavia M. Epifania, Pasquale Anselmi, Egidio Robusto
* [nettskjemar](https://github.com/CAPRO-UiO/nettskjemar) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2025-09-08 by Athanasia
  Mo Mowinckel, Trym Nohr Fjørtoft
* [riverbed](https://github.com/lvaudor/riverbed) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2023-02-16 by Lise Vaudor
* [bcgwcat](https://github.com/bcgov/bcgwcat/) ⭐ 1 | 🐛 9 | 🌐 JavaScript | 📅 2025-02-12 by Steffi LaZerte,
  Andarge Baye, Province of British Columbia
* [casteval](https://github.com/phac-nml-phrsd/casteval) ⭐ 1 | 🐛 9 | 🌐 R | 📅 2025-08-27 by Daniel Yu,
  Irena Papst, David Champredon, Government of Canada
* [ESPA](https://github.com/PratheepaJ/ESPA) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2018-09-20 by Jeganathan Pratheepa,
  Trindade, Alex
* [JTHelpers](https://github.com/jenniferthompson/JTHelpers) ⭐ 1 | 🐛 16 | 🌐 R | 📅 2017-02-22 by Jennifer
  Thompson, Cole Beck, Zhiguo Zhao
* [learnres](https://github.com/yabellini/learnres) ⭐ 1 | 🐛 3 | 🌐 HTML | 📅 2021-07-19 by Yanina Bellini
  Saibene
* [lmmpar](https://github.com/fulyagokalp/lmmpar) ⭐ 1 | 🐛 1 | 🌐 R | 📅 2017-08-03 by Fulya Gokalp Yavuz,
  Barret Schloerke
* [PCADSC](https://github.com/annennenne/PCADSC) ⭐ 1 | 🐛 0 | 🌐 TeX | 📅 2025-05-21 by Anne Helby Petersen,
  Bo Markussen
* [regscoreR](https://github.com/UBC-MDS/regscoreR) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2018-04-22 by Simran Sethi, Ha
  Dinh, Ruoqi Xu
* [smbdata](https://github.com/emitanaka/smbdata) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2026-01-21 by Emi Tanaka, Sue
  Welham, Salvador Gezan, Suzanne Clark, Andrew Mead
* [tailloss](http://github.com/igollini/tailloss) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2015-07-08 by Isabella Gollini,
  Jonathan Rougier
* [TextMiningTutorial](https://github.com/yabellini/TextMiningTutorial) ⭐ 1 | 🐛 0 | 📅 2021-05-19
  by Yanina Bellini Saibene
* [wcep](https://github.com/sarah-0k/wcep) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2026-06-11 by Jeffrey Bakal, Cynthia
  Westerhout, Sarah Rathwell, Caroline Falvey, Huiman Barnhart, Na Zhang
* [woody](https://github.com/lvaudor/woody) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2022-03-15 by Lise Vaudor
* [ARUtools](https://github.com/ARUtools/ARUtools) ⭐ 0 | 🐛 4 | 🌐 R | 📅 2025-11-17 by David Hope, Steffi
  LaZerte, Government of Canada
* [BayesCVI](https://github.com/o-preedasawakul/BayesCVI) ⭐ 0 | 🐛 0 | 📅 2024-09-05 by Nathakhun
  Wiroonsri, Onthada Preedasawakul
* [chartkickR](https://github.com/BWOlatunji/chartkickR) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-05-22 by Bilikisu
  Olatunji
* [cstime](https://github.com/csids/cstime) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2025-12-23 by Chi Zhang, Richard Aubrey
  White, CSIDS
* [escrocR](https://github.com/Irstea/escroc) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2022-10-07 by Hilaire Drouineau,
  Marine Ballutaud, Jeremy Lobry
* [GenBank](https://github.com/lucymli/GenBank) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2016-03-08 by Lucy M Li, Who to
  complain to
* [ggseg.formats](https://github.com/ggsegverse/ggseg.formats) ⭐ 0 | 🐛 3 | 🌐 R | 📅 2026-08-23 by
  Athanasia Mo Mowinckel, Center for Lifespan Changes in Brain and
  Cognition, University of Oslo
* [ggseg.meshes](https://github.com/ggsegverse/ggseg.meshes) ⭐ 0 | 🐛 1 | 🌐 R | 📅 2026-07-05 by
  Athanasia Mo Mowinckel, Center for Lifespan Changes in Brain and
  Cognition, University of Oslo
* [gnomesims](https://github.com/josefinabernardo/gnomesims) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-03-04 by Josefina
  Bernardo
* [HaplinMethyl](https://github.com/jromanowska/HaplinMethyl/) ⭐ 0 | 🐛 4 | 🌐 HTML | 📅 2025-03-31 by Julia
  Romanowska, Haakon K. Gjessing
* [levelup](https://github.com/trianglegirl/levelup) ⭐ 0 | 🐛 10 | 🌐 R | 📅 2024-08-20 by Rhian Davies
* [model4you](https://github.com/cran/model4you) ⭐ 0 | 🐛 1 | 🌐 R | 📅 2026-02-12 by Heidi Seibold, Achim
  Zeileis, Torsten Hothorn
* [saguaRo](https://github.com/sborrego/saguaRo) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2021-08-08 by Stacey Borrego
* [sendplot](https://github.com/lshep/sendplot) ⭐ 0 | 🐛 3 | 🌐 R | 📅 2017-11-06 by Daniel P Gaile,
  Lori A. Shepherd, Lara Sucheston, Andrew Bruno, Kenneth F. Manly
* [SeroTrackR](https://github.com/dionnecargy/SeroTrackR) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-06-05 by Dionne
  Argyropoulos
* [SPBB](https://github.com/PratheepaJ/SPBBspatial) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2018-12-05 by Pratheepa
  Jeganathan
* [TutorialIterar](https://github.com/yabellini/TutorialIterar) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2021-04-25 by
  Yanina Bellini Saibene
* [verdadecu](https://github.com/Demografiando/verdadecu) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-06-01 by Adriana
  Robles, Javier Borja
* [ADTSA]() by Hossein Hassani, Masoud Yarmohammadi, Mohammad Reza
  Yeganegi, Leila Marvian Mashhad
* [asciify](https://github.com/djnavarro/asciify) by Danielle Navarro
* [ASICS]() by Gaëlle Lefort, Rémi Servien, Patrick Tardivel, Nathalie
  Vialaneix
* [BayesERtools](https://genentech.github.io/BayesERtools/) by Kenta
  Yoshida, François Mercier, Danielle Navarro, Genentech, Inc.
* [biwt]() by Jo Hardin <jo.hardin@pomona.edu>, Jo Hardin
* [BLModel]() by Andrzej Palczewski, Jan Palczewski, Alicja Gosiewska
* [BlueCarbon]() by Valentina Costa, Márcio Martins
* [bs4cards](https://github.com/djnavarro/bs4cards) by Danielle Navarro
* [capesData]() by Leonardo Biazoli, Mine Çetinkaya-Rundel, Eric
  Fernandes de Mello Araujo, Izabela R. Cardoso de Oliveira
* [coseq]() by Andrea Rau, Cathy Maugis-Rabusseau, Antoine
  Godichon-Baggioni
* [covid19france]() by Amanda Dobbyn
* [covid19us]() by Amanda Dobbyn
* [CyTOFpower]() by Anne-Maud Ferreira, Catherine Blish, Susan Holmes
* [distory]() by John Chakerian, Susan Holmes, Emmanuel Paradis
* [dmrseq]() by Keegan Korthauer, Rafael Irizarry, Yuval Benjamini,
  Sutirtha Chakraborty
* [ern]() by David Champredon, Warsame Yusuf, Irena Papst
* [EZtune]() by Jill Lundell
* [GISINTEGRATION]() by Hossein Hassani, Leila Marvian Mashhad, Sara
  Stewart, Steve Macfeelys
* [Haplin](https://haplin.bitbucket.io) by Hakon K. Gjessing, Miriam
  Gjerdevik, Julia Romanowska, Oivind Skare
* [Hassani.SACF]() by Hossein Hassani, Masoud Yarmohammdi, Mohammad Reza
  Yeganegi, Leila Marvian Mashhad
* [Hassani.Silva]() by Hossein Hassani, Emmanuel Sirimal Silva, Leila
  Marvian Mashhad
* [hexify](https://github.com/djnavarro/hexify) by Danielle Navarro
* [hicream](https://forge.inrae.fr/scales/hicream/-) by Elise Jorge,
  Sylvain Foissac, Toby Hocking, Pierre Neuvial, Nathalie Vialaneix,
  Gilles Blanchard, Guillermo Durand, Nicolas Enjalbert-Courrech,
  Etienne Roquain
* [highriskzone]() by Heidi Seibold, Monia Mahling, Sebastian Linne,
  Felix Guenther, Rickmer Schulte
* [HTSCluster]() by Andrea Rau, Gilles Celeux, Marie-Laure
  Martin-Magniette, Cathy Maugis- Rabusseau
* [HTSFilter]() by Andrea Rau, Melina Gallopin, Gilles Celeux, Florence
  Jaffrézic
* [iAdapt]() by Alyssa Vanderbeek, Laura Cosgrove, Elizabeth
  Garrett-Mayer, Cody Chiuzan
* [infiltrodiscR]() by Carolina V. Giraldo, Sara E. Acevedo, Carlos A.
  Bonilla
* [jaysire](https://github.com/djnavarro/jaysire) by Danielle Navarro,
  Danielle Navarro
* [metaRNASeq]() by Guillemette Marot, Andrea Rau, Florence Jaffrezic,
  Samuel Blanck
* [mixKernel](https://forgemia.inra.fr/genotoul-bioinfo/mixKernel/-) by
  Nathalie Vialaneix, Celine Brouard, Remi Flamary, Julien Henry, Jerome
  Mariette
* [nestr]() by Emi Tanaka
* [NiLeDAM]() by Nathalie Vialaneix, Aurélie Mercadié, Jean-Marc Montel,
  Anne-Magali Seydoux-Guillaume
* [ordinalClust]() by Margot Selosse, Julien Jacques, Christophe
  Biernacki
* [oxcAAR]() by Hinz Martin, Clemens Schmid, Daniel Knitter, Carolin
  Tietze
* [pangaear](https://github.com/ropensci/pangaear%20\(devel\)) by Scott
  Chamberlain, Kara Woo, Andrew MacDonald, Naupaka Zimmerman, Gavin
  Simpson
* [partykit](http://partykit.r-forge.r-project.org/partykit/) by Torsten
  Hothorn, Heidi Seibold, Achim Zeileis
* [phoenics](https://forge.inrae.fr/panoramics/phoenics/-) by Camille
  Guilmineau, Remi Servien, Nathalie Vialaneix
* [PreProcessRecordLinkage]() by Hossein Hassani, Leila Marvian Mashhad
* [ProliferativeIndex]() by Brittany Lasseigne, Ryne Ramaker
* [psychomix]() by Hannah Frick, Friedrich Leisch, Carolin Strobl,
  Florian Wickelmaier, Achim Zeileis
* [qsmooth]() by Stephanie C. Hicks, Kwame Okrah, Koen Van den Berge,
  Hector Corrada Bravo, Rafael Irizarry
* [quantro]() by Stephanie Hicks, Rafael Irizarry
* [rainbowr](https://github.com/djnavarro/rainbowr) by Danielle Navarro
* [rddapp]() by Ze Jin, Wang Liao, Irena Papst, Wenyu Zhang, Kimberly
  Hochstedler, Felix Thoemmes
* [RNAseqNet]() by Alyssa Imbert, Nathalie Vialaneix
* [RUVcorr]() by Saskia Freytag
* [shinycustomloader]() by Emi Tanaka and Niichan
* [SISIR](https://forgemia.inra.fr/sfcb/sisir/-) by Victor Picheny, Remi
  Servien, Nathalie Vialaneix
* [superheat]() by Rebecca Barter, Bin Yu
* [TEQC]() by M. Hummel, S. Bonnin, E. Lowy, G. Roma, Sarah Bonnin
* [treediff](https://forge.inrae.fr/scales/treediff/-) by Nathalie
  Vialaneix, Gwendaelle Cardenas, Marie Chavent, Sylvain Foissac, Pierre
  Neuvial, Nathanael Randriamihamison
* [UniversalCVI]() by Nathakhun Wiroonsri, Onthada Preedasawakul
* [XICOR]() by Susan Holmes, Sourav Chatterjee
* [zalpha]() by Clare Horscroft, Clare Horscroft

## License

[![CC0](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
