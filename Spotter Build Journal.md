Spotter Build Journal

Date: October 12, 2026
Stage: Product definition and preparation for development

I started Spotter with a raw idea for an app that helps gym members get answers to their questions without having to rely on the receptionist. Before jumping into design or development, I wanted to understand the problem better, identify gaps I might have missed, and refine the idea into something more concrete.

I began by building the context around the idea. This helped me examine the problem, challenge my initial assumptions, and clarify what the product should actually do.

One thing I established was that Spotter isn't just a gym chatbot. It's a retrieval system built around the gym's own private records. It needs to distinguish between general gym information, such as timetables and membership policies, and personal member information, such as attendance, payment history, and outstanding balances. Each type of information has different access requirements, and personal records must remain private to the individual member.

I also considered how answers should be presented. Rather than simply returning a response, Spotter should show the actual record supporting that answer and when it was last confirmed. If the necessary information isn't available, the app shouldn't guess.

After refining the idea and identifying these requirements, I created a Product Requirements Document (PRD) to define the product's scope, features, and expected behaviour.

I then used the PRD to create an AGENTS.md file, giving the AI coding agent project-specific context and instructions to follow during development. I wanted the agent to have a clearer understanding of what I was building before it started writing code.

One important decision was keeping the first version focused. Spotter's initial scope covers information retrieval, attendance tracking, and subscription payments. Features such as automated reminders, follow-ups, and agentic workflows are deferred to version two.

This process reminded me that developing an idea involves more than deciding which features to include. It also means identifying boundaries, thinking through how information should flow, considering privacy, and deciding what the product should not do yet.