[linux][devops] [python]  [devops]


by Mischa Van den Burg

"Now that AI can do all of our coding, should I still learn to code?"

Someone asked me this during a live coaching session in [KubeCraft](https://ed9688f7.click.kit-mail3.com/27uqe5g5gkboh86567wu3hg3nggz3h0n077prrdlkpm3rqqv95kpd25p99x7no70zvqp88905eogrr606lz8zqll8v26455eo2rk7lgdl907ln4005zm9804gedcgqp85/25h2hoh369mk2ns3/aHR0cHM6Ly9rdWJlY3JhZnQuY2xpY2svZWM2Mzc3) this week, and I think it's the most important question in DevOps right now.

Short answer: yes. Let me explain why.

## Why DevOps Engineers need to write code

Some people describe DevOps Engineers as "system administrators who learned how to code", and I think that's accurate.

In the old days, software was literally deployed by copying files to servers and starting them by hand.

In modern DevOps, we use software to do these tasks for us.

GitHub Actions to test code and build the container image. GitOps to deploy that image to Kubernetes.

These systems were created by writing code. So when something goes wrong (and it will!) - you need programming skills to solve the problem.

You also need coding skills to work with Infrastructure as Code. Any modern self-respecting cloud environment deploys through Terraform, Bicep, or Pulumi.

And sometimes you'll build internal tooling. CLI's, API's, Kubernetes operators that make your life and the life of your developers a lot easier.

This is why any DevOps roadmap worth following will tell you to learn at least one programming language.

At least until now. So is it still required?

## AI works as an amplifier, not a replacement

I'm not a software engineer, but I love writing code. During my career I've written CLI tools, API's that stored and retrieved data from Postgres databases, and thousands of lines of bash for CI/CD pipelines.

These projects used to take days or weeks to complete.

Today, I can write most of them in an hour, and the result is better than when I'd write them myself.

That's a hard one to admit, but it's the truth.

However, there's one important nuance:

I can write these tools in an hour because I know how to prompt the AI. I give it detailed specifications — what I want, what I don't want, which libraries to use — and I can provide that level of detail because I've done it by hand for years.

I've gone through the errors. I've spent hours debugging. I know where to look when something breaks.

If I didn't have that experience, I'd be staring at AI output with no idea whether it's correct, no idea where to look when it fails, and no ability to guide it toward what I actually need.

Writing code teaches you how computers think. You learn to give instructions and get machines to perform actions for you.

This is a fundamental skill if you want to work with computers for a living.

## How to learn to code

When you find yourself on a command line on Friday at 4pm trying to fix an issue, AI is not going to save you. You need debugging skills that can only be learned through practice.

Here's what I recommend as a learning path:

1. Start with Linux, and do everything on Linux
2. Write all your code in vim.
3. Learn how to write bash scripts.
4. Learn the fundamentals of at least one programming language.
5. Build a few small projects that solve a problem in your life.

The best language to start with is Python. It's used everywhere and easy to pick up.

After that comes Go — steeper learning curve, but it will make you a better programmer.

Some great free resources to get started.

Harvard's full 16-hour Python course:
https://www.youtube.com/watch?v=nLRL_NcnK-4



If you prefer books: [https://nostarch.com/python-crash-course-3rd-edition](https://ed9688f7.click.kit-mail3.com/27uqe5g5gkboh86567wu3hg3nggz3h0n077prrdlkpm3rqqv95kpd25p99x7no70zvqp88905eogrr606lz8zqll8v26455eo2rk7lgdl907ln4005zm9804gedcgqp85/g3hnh5hmr9q43rbr/aHR0cHM6Ly9ub3N0YXJjaC5jb20vcHl0aG9uLWNyYXNoLWNvdXJzZS0zcmQtZWRpdGlvbg==)​

For exercises, I recommend [https://exercism.org](https://ed9688f7.click.kit-mail3.com/27uqe5g5gkboh86567wu3hg3nggz3h0n077prrdlkpm3rqqv95kpd25p99x7no70zvqp88905eogrr606lz8zqll8v26455eo2rk7lgdl907ln4005zm9804gedcgqp85/9qhzhnhd0w5opwt9/aHR0cHM6Ly9leGVyY2lzbS5vcmc=) — they let you do coding exercises from your own CLI.

Always code from the CLI in Vim. That's what Craftsmen do.

Have a great week,

Mischa