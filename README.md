### Welcome to the Early Access Program (EAP) for Edge Functions

We're excited to have you participate in Vercel's EAPs. In this repository, you will find everything you need to get started testing Vercel's Edge Middleware features.  

Edge Middleware is a Vercel technology that allows our customers to run Javascript code at the Edge right before a request is processed. Based on the incoming request shape, the customer can perform effects on the response such as rewriting, redirecting, adding headers or intercepting the request and respond. This enables a number of interesting features such as performing effects based on the user agent, A/B testing, country blocking, etc.

**How to use this repository**

We are running the Early Access Program (EAP) through this repository. In it you'll find everything you need to get set up with the feature, provide feedback, and dive into examples so that you can begin trying things out yourself. 

**Get started:** 

1. Download the [packed version](https://next-middleware-build.vercel.sh/next-v12.0.0-nightly.7.tgz) of Next. Since it's an unreleased version of Next.js, you will have to point to this version from [`package.json`](package.json#L11).

2. The runtime required to build Next.js with the Edge Middleware is not publish yet either so you will have to require the project to use the specific dev builder version like in the [`vercel.json`](vercel.json#L5) file of this repo.

**Read the docs:** 

We are writing the docs similarily to how we write code: iteratively and alongside the featureset. You can [read the docs here](https://github.com/vercel-customer-feedback/edge-middleware/blob/main/docs/docs.md), they're part of this repository. If you have any questions or suggestions about the docs, feel free to [open a discussion](https://github.com/vercel-customer-feedback/edge-middleware/discussions), or [submit a PR](https://github.com/vercel-customer-feedback/edge-middleware/pulls) with your suggestions! 

**Provide feedback:**

We are collecting feedback right here in this repo using Discussions and Issues. How do you know if you should open a discussion or an issue? 

1. **Discussion post:** a question, piece of feedback, or idea you have about the feature that you would like to discuss with the team. 
2. **Issue:** Open a GitHub issue if you believe you've encountered a bug that you want to flag for the team. We may commend and kick off a conversation about the bug in the issue thread. 


