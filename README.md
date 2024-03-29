# Dusk Improvement Proposals (DIPs)

Welcome to the official repository for Dusk Improvement Proposals (DIPs). This platform serves as a centralized hub for community-driven proposals aiming to refine, upgrade, and innovate within the Dusk Network ecosystem.

## What is a DIP?

A Dusk Improvement Proposal (DIP) is a formal document that proposes a new feature, standard, or protocol adjustment within the Dusk Network. DIPs are the primary mechanism for proposing new features, collecting community input on an issue, and documenting the design decisions that have gone into the Dusk Network. They are meant to be the source of truth for Dusk Network improvements, serving both as a historical document and a detailed explanation of the feature and its purpose.

## Purpose

The DIP repository is intended to provide a structured process for making substantive changes to the Dusk Network. Its goals are to:

- Ensure that proposed improvements are thoroughly discussed and evaluated
- Create a transparent and inclusive process for governance
- Facilitate the collection and documentation of a coherent and comprehensive history of governance and feature proposals
- Encourage active community participation and collaboration

## DIP Statuses

- **Draft**: The DIP has been accepted for review.
- **Review**: The DIP is undergoing community review and feedback.
- **Last Call**: The DIP is nearing finalization; this is the final review window for the community.
- **Accepted**: The DIP has been accepted and is either awaiting implementation or has been implemented.
- **Final**: The DIP has been implemented and is now a part of the Dusk Network protocol.

## How to Propose a DIP

1. **Familiarize Yourself with Existing DIPs**: Before drafting a new proposal, please review the existing DIPs to ensure your idea is unique and not already covered.

2. **Draft Your Proposal**: Following the [DIP Template](https://github.com/dusk-network/dips/issues/1) specification, the [template structure for a DIP follows](#dip-structure). Your DIP should provide a concise specification of the feature and a rationale for the feature.

3. **Submit Your DIP**: Fork the repository, add your DIP draft to the `dips` directory using the naming convention `dip-<number>.md`, where `<number>` is your proposed DIP number. Then, submit a pull request (PR) against the main branch of the Dusk Network DIPs repository.

4. **Discussion and Review**: The DIP will undergo a review and discussion phase where the community and DIP editors will provide feedback. Be prepared to revise your draft in response to feedback.

5. **Finalization**: Once accepted, the DIP editors will assign a DIP number, merge your PR, and track the progress of the DIP implementation.

### DIP Structure

Each Dusk Improvement Proposal (DIP) must adhere to the following structure so as to ensure clarity and consistency across proposals.

1. **Preamble**
    - **DIP Number:** (To be assigned upon acceptance)
    - **Title**
    - **Author(s):** Contact information and GitHub usernames
    - **Status:** (Draft, Review, Accepted, Final, Rejected)
    - **Category/Type:** (Core, Standards, Governance, etc.)
    - **Creation Date**

2. **Abstract**
    - A concise technical summary of the proposal.

3. **Motivation**
    - Describes the issue being addressed and why the proposal is necessary.

4. **Technical Specification**
    - Detailed description of the proposed changes, including protocol changes, data structures, API alterations, and cryptographic considerations.

5. **Rationale**
    - Discussion on the decision-making process and trade-offs considered.

6. **Backwards Compatibility**
    - Analysis of how the proposal interacts with existing features or might affect backward compatibility.

7. **Test Cases**
    - Practical examples and test cases for validating the proposed changes.

8. **Implementation**
    - Reference to the implementation code; this may include links to PRs in external repositories.

9. **Security Considerations**
    - Assessment of potential security implications and how they are addressed.

10. **References**
    - Links to any related documents, discussions, or other relevant materials.

11. **Updates (Optional)**
    - Documenting significant changes or updates to the proposal post-acceptance.

## DIP Workflow

The Dusk Improvement Proposal (DIP) process is designed to provide a transparent and structured approach to proposing improvements within the Dusk protocol. Each DIP follows a clear path from inception to finalization:

1. **Idea:** The process begins with an initial concept or idea discussed informally within the community.
2. **Draft:** Once the idea has been sufficiently fleshed out, a formal draft is created to detail the proposal.
3. **Feedback:** The draft is then reviewed by the community and stakeholders, where it can be refined and improved based on `Feedback`.
4. **Staging:** After the review, the proposal enters the `Staging` phase, indicating it is nearing completion and providing a final chance for feedback.
5. **Final:** If the DIP receives consensus, it is marked as Final and is implemented within Dusk.

Additionally, proposals can be transitioned to a **Stagnant** state if they are not actively being developed or considered. A proposal might also be **Dead** by the author(s) if it is no longer pursued. A DIP can also exist in a **Iterating** state as a document that is updated over time without needing a new DIP number.

Below is a diagram that illustrates the DIP workflow:

    ![DIP-diagram](https://github.com/dusk-network/dips/assets/7613527/c6f75781-6f96-4bdb-b28c-3a34dfccfaeb)

For more information on how to contribute to the DIP process, please see the [CONTRIBUTING.md](https://github.com/dusk-network/.github/blob/main/.github/CONTRIBUTING.md) file.


## Contributing

We welcome contributions from everyone. For more details on how to contribute, please read the [CONTRIBUTING.md](https://github.com/dusk-network/.github/blob/main/.github/CONTRIBUTING.md) file.

## License

This repository is licensed under [Mozilla Public License Version 2.0.](https://github.com/dusk-network/rusk/blob/master/LICENSE).

## Contact

For further inquiries or proposals, please open an issue in this repository.
