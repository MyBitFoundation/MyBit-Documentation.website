<div align="center">
    <img src="https://github.com/MyBitFoundation/MyBit-Documentation.website/blob/master/MyBit-logo.png?raw=true" width="150px">
</div>

<h2 align="center">MyBit Product Requirements Document (PRD)</h2>

<p align="center">
    Version 1.0.0 - Latest update 29.03.2019
</p>

<p align="center">
    This Product Requirements Document (PRD) describes all the specifications and product requirements for the MyBit product, including functionality, use cases, scenarios as well as descriptions of the users interacting with the system and the technology behind it.
</p>

<p align="center">
    Ian Worrall - CEO & Founder (ian@mybit.io) <br />
    Jose Aguinaga - Head of Engineering (jj@mybit.io) <br />
    Cristiano Martins - Front-End Lead (cris@mybit.io) <br />
    Peter Phillips - Blockchain Lead (pm@mybit.io) <br />
    Konstantin Dmitriev - Lead Designer (kd@mybit.io)
</p>

### Goals and Context


#### What is the goal?

Create a new brand PRD template that we can use across our applications taking in consideration the current DApp ecosystem, thus considering, for example, non-functional features like a proper user experience with Metamask.


#### What problem does this project solve?

Target web applications that perform interactions with Ethereum contracts and provide a baseline for Product Owners to describe the functionality, scope, and other expectations about the application to be developed.


#### What is the vision?

Target web applications that perform interactions with Ethereum contracts and provide a baseline for Product Owners to describe the functionality, scope, and other expectations about the application to be developed.


### User Personas

The **User Personas** are the possible users that can interact with our platform, and perform actions against it through a series of authenticated operations.


<table>
    <tr>
        <td><strong>Role</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Actions</strong></td>
    </tr>
    <tr>
        <td><strong>Visitor</strong></td>
        <td>Any users that go to our website, and wants to learn more about the platform and listed assets.</td>
        <td>Browse all assets, see information about these assets, share assets, subscribe to assets.</td>
    </tr>
    <tr>
        <td><strong>Investor</strong></td>
        <td>Any visitor that connects to a Metamask account, and is looking into doing an investment to an asset within the platform.</td>
        <td>All actions of a visitor, plus invest in a specific asset, see a portfolio of their investments, see all transactions made in the platform, watch and asset, withdraw revenue, and list an asset.</td>
    </tr>
</table>



### User Stories


#### Visitor

**As a visitor, I want to be able to see all listed assets in the platform, so that I know whether I'm interested in any of them.**

*   I want to see the name of the asset to be invested (e.g. Smart Bench, Warehouse Unit)
*   I want to see the percentage the asset has been funded (e.g. 50%, 100%)
*   I want to see the goal the asset is trying to reach (e.g. 10,000 DAI, 2,000 DAI)
*   I want to see the owner of the asset manager (e.g. IoT LLC, Enterprises AG)


#### Investor

**As an investor, I want to be able to invest into a specific asset so I can get a promised return of investment based on the information of the asset.**

*   I want to be able to select a specific amount of DAI to invest into the project. (e.g. 10)
*   I want to be able to see a breakdown of the percentage going to the project and which project goes to the manager (e.g. 10% and 0.5%, 12% and 0.2%).


### Non-Functional Requirements

1. No buttons triggering an action should be enabled unless that action can be performed by the user.
    1. Accepting Terms and Conditions.
    2. Connect to Metamask.
2. All transactions should provide a notification channel with a "Go to Etherscan" to visualize the transaction in question.
3. Transaction changes into the application should be able to reflect a change of state in a way the user can see it. E.g. Investing into an item should update the "Portfolio" section.
4. If there are any Blockchain transactions/data we are waiting for, we should be able to always notify the user about it in a way that they know it's still missing information.
5. Any list of records that exceed more than 10 records on screen should have a navigation bar to display the next ones
6. All images and documents uploaded into the application must have a hard limit of 5 MB.
7. Ideally, we decentralise our infrastructure from the following services:
    1. Images and Assets -  From AWS to IPFS
    2. Database queries - From Airtable to TheGraph
    3. Data queries - From local servers to TheGraph


### Pages

The different pages across the web application that can be browsed by different type of users depending on their roles within the system.


<table>
    <tr>
        <td><strong>Page</strong></td>
        <td><strong>Description</strong></td>
    </tr>
    <tr>
        <td>Landing Page (/)</td>
        <td>Landing screen for users and investors alike, with enough information to get by.</td>
    </tr>
    <tr>
        <td>Onboarding (/onboarding)</td>
        <td>Initial screen for new users that are visiting the application for the first time.</td>
    </tr>
</table>


### User Interaction and Design, Roadmap and Iterations

Everything related to the MyBit Go project design wise can be found in our [Figma](https://www.figma.com/file/St3i6IrIvXxWY7vlSsdsRatZ/MyBit-Go-v2) project, and a project roadmap can be found in our [Basecamp](https://public.3.basecamp.com/p/FTG9md1KBwLP5dJAoZsLuPAK) project. Incoming features wise can be found in our [Basecamp](https://public.3.basecamp.com/p/FTG9md1KBwLP5dJAoZsLuPAK) project.
