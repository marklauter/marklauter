# [Mark Lauter](https://www.linkedin.com/in/marklauter/)

Cloud Solutions Architect at [Insight](https://www.insight.com/). I design and build cloud-based distributed systems for clients. After hours, I write database internals.

## I like graphs

A graph is only as good as the storage engine beneath it, and those are hard — so I'm building the pieces in the open, one at a time: a [SQL parser](https://github.com/marklauter/sql-parser) for the Code Crafters SQLite challenge, [data pages](https://github.com/marklauter/pages), a [B-tree](https://github.com/marklauter/btree), a [buffer pool](https://github.com/marklauter/buffer-pool), and a [write-ahead log](https://github.com/marklauter/write-ahead-log).

I'm still working out how transactions coordinate the buffer pool and the write-ahead log. If you can explain it cleanly, open an issue.

Graphs run through access control, too. [kingo](https://github.com/marklauter/kingo) is my clone-in-progress of Google's Zanzibar — a graph problem and a little-language problem at once: the relation tuples form the graph you traverse, and the userset rewrite rules are a small expression language.

## I like expression trees

I wrote my first domain-specific language in 1996, for an electric utility billing system. A second followed in 1998, for server-side dynamic HTML rendering. A third in 2008: a query language for a custom GIS database with temporal-spatial sharding. Lately I've been rebuilding the craft from the ground up — a [lexer](https://github.com/marklauter/lexi) and a [recursive-descent interpreter](https://github.com/marklauter/interpreter-redux).

I've programmed professionally in FORTRAN, C, C++, Delphi, C#, BASIC, VB.Net, Java, JavaScript, TypeScript, Python, Perl, LISP, and a few obscurities like Object PAL. Pressed for a favorite, I'd name C# and C. I'm slowly catching up on functional programming, because monads make me happy.

## I like pools and pipelines

[pool](https://github.com/marklauter/pool) is an object pool for dotnet; [plumber](https://github.com/marklauter/plumber) is a request-response middleware pipeline built for AWS Lambda, with a [Serilog extension](https://github.com/marklauter/plumber.serilog.extensions) to match. I also keep [DynamoDbLite](https://github.com/marklauter/DynamoDbLite), a DynamoDB emulator on SQLite, in active development. All three run in real-world projects.

## I like things that fly and things that go beep

Hillsborough County's gifted program introduced me to computer programming and [lambda calculus](https://en.wikipedia.org/wiki/Lambda_calculus) when I was nine. That was 1978. After high school I served in the [US Army](https://www.army.mil/) as a crew chief on AH-1 Cobra attack helicopters. These days I fly small planes, hold an airframe mechanic's certificate, and write a [flight controller for the Tello drone](https://github.com/marklauter/TelloAPI-SDK-2.0) for fun.

When the desert lost its charm, I came home to Florida, shook the rust off my brain, and joined the engineering co-op at [Tampa Electric](https://www.tampaelectric.com/) in 1993. Its sister company TeCom hired me as a software engineer in 1995. Since then — early internet startups, IoT and GIS shops, machine-vision startups, and several fintechs — I've built a few systems at real scale: a GPS tracking platform running 1.3 trillion geofence evaluations a day, an asset tracker watching 650,000 devices, and a verifications pipeline that grew 100x. For 18 years I ran my own [software consulting firm](https://www.linkedin.com/company/sumo-software-corporation/).

## Reach me

Open an issue on this repo, or find me on [LinkedIn](https://www.linkedin.com/in/marklauter/). Ask me about anything.

---

Fun fact: my first computer was a room I never saw. I reached it through a [Teletype Model 37](https://www.youtube.com/watch?v=MikoF6KZjm0) that printed every screen refresh in full — bang, shake, rumble, pop, beep — while we played [Star Trek](https://makinggamesbyyear.itch.io/star-trek-1971). It shook the whole room. Most amazing thing I'd ever seen. Decades later I rebuilt that game [in C#](https://github.com/marklauter/Trekish).
