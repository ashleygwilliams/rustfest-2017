# rustfest-2017

## abstract

I made one of my favorite pull requests ever on December 17, 2016:

[`rust-www/pulls/634: add npm to friends page`](https://github.com/rust-lang/rust-www/pull/634)

On any given day, the npm registry, a repository of packages primarily for JavaScript and Node.js, serves around 350,000,000 package downloads. The npm services team is small and this once little Node.js service, the lifeblood of the modern web development workflow, is now a huge set of microservices- and starting in late 2016, it’s no longer just Node.js- it’s running production Rust.

In this talk, I’ll tell the story of how I convinced my manager and team to give Rust a chance. Along the way, I’ll talk about the critical challenges that the npm registry services encounter on a daily basis, the patterns we’ve adopted to cope with the heavy operational load, and how they are well suited to be solved with Rust. I’ll also highlight the unique aspects of Rust that make it an pleasure to learn and teach, as well as how it is a strong technical candidate for replacing Node.js (hint: Tokio!).

At the end of the talk, you will have a keen understanding of what problems Rust is good at solving and feel motivated and empowered to start the conversation about bringing Rust into your own organization.
