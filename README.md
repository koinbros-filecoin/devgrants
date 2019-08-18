# devgrants

![Filecoin Grants logo](img/filecoin-grants-logo.svg)

> Hello and welcome to the home page of the Filecoin Dev Grants program! If you haven't already checked it out, you can read more about the motivations behind the program on [the Filecoin website](https://filecoin.io/grants).

> **Note:** The Filecoin Project is still under active development, and the Filecoin network has not yet launched. You can see updates about major project milestones on [the Filecoin blog](https://filecoin.io/blog).

- 🥅 [Goals of Filecoin Devgrants](#goals-of-filecoin-devgrants)
- 🔎 [What we fund](#what-we-fund)
  - [Types of grants](#types-of-grants)
  - [Categories](#categories)
- 📋 [How to apply](#how-to-apply)
  - [Timing and Deadlines](#timing-and-deadlines)
  - [Submit a proposal for an RFP](#submit-a-proposal-for-an-rfp)
  - [Submit a proposal for open grants](#submit-a-proposal-for-open-grants)
- ⌛ [After you apply](#after-you-apply)
- ℹ️ [Help](#help)
- [License](#license)

## 🥅 Goals of Filecoin Devgrants 

To date, the Filecoin project has focused primarily on research, specification and implementation of a decentralized storage network protocol. Throughout this process we have been fortunate to work with incredible community members and contributors. Some are already building tools on the budding network in active development.

We created the Filecoin Dev Grants program to:
- Reward ongoing & existing contributions that add great value to the Filecoin ecosystem
- Inspire more contributors to solve open problems and engage with the Filecoin project
- Seed the creation of new products, businesses and tools to increase the utility of Filecoin

We’re looking to fund talented and eager teams that want to work with us to build a more robust, efficient, and decentralized web.

## 🔎 What we fund 

### Types of grants

We currently offer 2 types of grants:
1. **Requests for Proposals (RFPs)**: RFPs are grants for specific development work. As the name suggests, we are requesting proposals from teams that want to complete the work specified in each RFP. In these grants, we generally have clearly scoped *deliverables, milestones, and funding limits*. Some RFPs will ask you to propose your own milestones and funding needs. While there is some flexibility in RFP deliverables, we expect teams will deliver what is in scope in the RFP. Any deviations from the specified scope must be approved between your team and ours before we can approve funding. See [RFP submission details](#submit-a-proposal-for-an-rfp) for more information on how to apply for RFPs. Relevant proposals will be labeled [`proposal-type:rfp`](https://github.com/filecoin-project/devgrants/labels/proposal-type%3Arfp).
2. **Open grants**: If you have an idea for something that isn't covered by an open RFP, you can submit a proposal to our open grants category! This is where you get to be really creative; we can't wait to see what you propose! We will review these proposals on the same cadence as RFP proposals (i.e. once every quarter, read more about timing in [Timing and Deadlines"](#timing-and-deadlines)). See [open grant submission details](#submit-a-proposal-for-open-grants) for more information on how to submit a proposal. Relevant proposals will be labeled [`proposal-type:open-grants`](https://github.com/filecoin-project/devgrants/labels/proposal-type%3Aopen).

### Categories

All of our RFPs and open grants fund work in a few core categories. Over time, these categories may change/expand, so please keep a watch on this space!

- **Core development**: The Filecoin Project is currently focused on core protocol research, specification, and implementation. Through this program, we may occasionally fund collaborators to tackle core protocol implementation work. Relevant proposals will be labeled [`category:core-dev`](https://github.com/filecoin-project/devgrants/labels/category%3Acore-dev).
- **Application development**: As we continue to build out our developer platform, we would love to work with talented application developers to build useful and delightful applications that utilize Filecoin as the decentralized storage layer. Relevant proposals will be labeled [`category:app-dev`](https://github.com/filecoin-project/devgrants/labels/category%3Aapp-dev).
- **Developer tools and libraries**: We are always looking for ways to make the lives of Filecoin developers easier. This includes developer tools and libraries for both core protocol developers and application developers. Dev tools at all layers of the stack are invaluable! Relevant proposals will be labeled [`category:devtools-libraries`](https://github.com/filecoin-project/devgrants/labels/category%3Adevtools-libraries).
- **Technical design**: The Filecoin protocol will continue to evolve over time. Several planned protocol upgrades are already being researched, but we want to find the best technical designs for these planned upgrades and for ideas that aren't currently on our radar. This type of technical design work can be improvements to our core storage protocol, cryptoeconomics design, and more! Relevant proposals will be labeled [`category:technical-design`](https://github.com/filecoin-project/devgrants/labels/category%3Atechnical-design).
- **Documentation**: Having great documentation is crucial for any open-source project and development platform. This category includes how-to guides, protocol concepts, API docs, and more. If you think we need to create or improve existing documentation, please submit a proposal! Or apply to one of our open docs RFPs. Relevant proposals will be labeled [`category:docs`](https://github.com/filecoin-project/devgrants/labels/category%3Adocs).

## 📋 How to apply

### Timing and Deadlines

We will start a new grants cycle, or `wave`, every quarter i.e. every 3 months. Therefore, the last day of each quarter is the deadline for all proposals in that wave. 

Concretely, here are the deadlines for waves 1 and 2:

| Wave No. | Wave Opens | Wave Deadline |
| --- | --- | --- |
| 1 | August 19, 2019 | September 30, 2019, 11:59PM PT |
| 2 | October 1, 2019 | December 31, 2019, 11:59PM PT |

After the wave deadline, we will spend a few weeks reviewing proposals on GitHub, leaving comments, asking questions, and requesting changes. Ultimately, we approve or reject each proposal that was submitted within each wave. Our aim is to do this within 2 weeks after each wave deadline. Please note that if your team isn't responsive on GitHub, or doesn't provide the information requested in a timely fashion, your proposal likely will not be accepted. So pay attention to GitHub after you submit your proposal!

Note that there is a chance (but no guarantee) your proposal will be reviewed earlier than the wave deadline, and grants are awarded on a rolling basis so earlier strong proposals might have a slight advantage. Of course, there is no guarantee that we will review proposals before the deadline, so it's up to you whether you want to submit well before the deadline or not!

### Submit a proposal for an RFP

All of our currently open RFPs are listed [in the `rfps` folder](rfps/).

Here are the steps to submit a proposal against one of the listed RFPs!
1. Select an RFP you would like to apply for.
2. Submit a PR against the [`rfp-proposal-template.md` file]() in the [`rfp-proposals` folder]() of this repo. Make sure to fill in all the categories of the RFP proposal template (incomplete proposals will not be considered). Rename your file `project-title.md`, making sure to replace `project-title` with the name of your project.
3. Tag your PR with the appropriate tags:
  - Category tag: one of `category:core-dev`, `category:app-dev`, `category:devtools-libraries`, `category:technical-design`, `category:docs`
  - Grant type tag: Since this proposal is in response to an RFP, tag your PR with the `proposal-type:rfp` tag.

**Remember to submit your PR before the wave deadline. PRs submitted after the deadline will be considered in the next wave (at which point, the RFP might be closed).**

### Submit a proposal for open grants

Here are the steps to submit a proposal for the open grant category!
1. Submit a PR against the [`open-proposal-template.md` file]() in the [`open-grant-proposals` folder]() of this repo. Make sure to fill in all the categories of the proposal template (incomplete proposals will not be considered). Rename your file `project-title.md`, making sure to replace `project-title` with the name of your project.
2. Tag your PR with the appropriate tags:
  - Category tag: one of `category:core-dev`, `category:app-dev`, `category:devtools-libraries`, `category:technical-design`, `category:docs`
  - Grant type tag: Since this proposal is in the open grants category, tag your PR with the `proposal-type:open` tag.

**Remember to submit your PR before the wave deadline. PRs submitted after the deadline will be considered in the next wave (which means a 3-month delay in review for your proposal).**

## ⌛ After you apply

After you submit your proposal -- assuming you get it in by the deadline -- you can expect the following to occur:

- After the wave deadline, we will review all PRs tagged as either [`proposal-type:rfp`]() or [`proposal-type:open`](). During our review, we will add comments, questions, change requests, etc, on your team's PR.
- After a few round trips of discussion, our team will make a decision on which proposals to fund and which not to. Accepted proposals will be merged into the appropriate directory, i.e. either [`open-grant-proposals`]() or [`rfp-proposals`]().
- During the discussion and review phase, our team will contact your team for financial and legal follow-ups, such as to confirm milestones and funding, your team's legal structure, etc.
- If your team is accepted, we will ask you to sign our Open Source Software Grant Agreement (TODO link), which will include a copy of the work plan and funding milestones. Note that if your team does not meet the acceptance criteria for the grant (whether it's an RFP or open grant), we may stop funding your team for further development work.
- We aim to complete all review within 2 weeks after the wave deadline, so please stay vigilant on GitHub. If we don't hear back from you when we ask you a question or request changes on your proposal, it's very unlikely that your proposal will be accepted!

## ℹ️ Help

Check out [these resources](https://filecoin.io/resources/) to get learn more about Filecoin.

Join the conversation at
- Our [community forum](https://discuss.filecoin.io). Ask your questions here first!
- [Community chat](https://github.com/filecoin-project/community#chat)

## License

The Filecoin Project is dual-licensed under Apache 2.0 and MIT terms:

- Apache License, Version 2.0, (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
- MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)
