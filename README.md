![alt text](img/moonpig-logo.png "Moonpig")

# Backend Technical Challenge

We'd like you to build a simple API to calculate estimated dispatch dates for products.

The API should allow a client to supply an **order** and receive the estimated Post Office **dispatch date** for the order.

The rules for dispatch dates are:

1. An order consists of a list of **product IDs**.
1. Each **product** has an associated **supplier**.
1. Each **supplier** has a **lead time**, which is the time in days it takes for its products to reach Moonpig's Post Office for dispatch.
1. Orders will only be dispatched once all of the items in the order have been received by the Post Office.
1. Once the product reaches the Post Office, it will be dispatched on the same day, _except_ on weekends. If the Post Office receives the product on a weekend, the product will be dispatched on the following Monday.

## Out of scope

The following are outside of the scope of this task:

1. Bank holidays. Assume the Post Office works all days except for Saturday and Sunday.
1. Cut-off times. The dispatch date estimate should produce the same result regardless of the time of day.

## Technical requirements

1. Complete your solution in TypeScript or C#.
1. Support JSON as a request/response format.
1. Use Git for version control.
1. Hard-coding data is fine for the purposes of the project, but think about organising your code so that replacing your hard-coded data with a database would be safe and straightforward. Feel free to use the sample data in the `data` directory.

## What we're looking for

1. **How you set up your project.** A clear folder and project structure. Code that builds and runs out of the box and clear documentation of how to do so.
1. **How you design your solution.** A considered approach to both the design of the API contract and a clean, simple implementation. Your code should be testable and extensible, but no more complex than it needs to be to do the job.
1. **How you approach testing.** An effective, practical approach to automated tests with a good level of coverage. Ideally you'll show evidence of a test-first approach where appropriate.
1. **How you use version control.** There are no hard and fast rules here, but we expect you to demonstrate a pragmatic use of version control. Frequent commits are better.

## What we're not looking for

1. **Cross-cutting concerns** like logging, monitoring and authentication.
1. **Specific coding conventions,** as long as you are clear, consistent and concise.
1. **Complexity.** Keep things simple and straightforward.

## How do I submit my solution?

Please submit your code - including the Git repository - according to the directions given to you by the recruiter who sent you the test.

Also submit a README file detailing:

1. How to build, test, run and call your application.
2. A brief description of your approach and any key assumptions and design decisions you made during implementation (250 words max).

If you'd like to, feel free to also host your working solution somewhere and send us a link.

## How long should I spend on this?

Your time is important. We're anticipating that you'll spend **2 to 3 hours** working on this from start to finish. Please try and limit yourself to not much more than that.

Remember that this project is designed for us to get a gauge on your approach and give us something to discuss with you face-to-face - we aren't looking for perfection. If there are things you'd like to have done but didn't have time - just make a note in your README.
