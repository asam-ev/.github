# :book: Contributing to ASAM e.V. open-source Projects

As an open-source standardization projects, we welcome and encourage the community to submit patches directly to the project. In our collaborative open source environment, standards and methods for submitting changes help reduce the chaos that can result from an active development community. This document explains how to participate in project conversations, log bugs and enhancement requests, and submit patches to the project so your patch will be accepted quickly in the codebase.

All intellectual property remains with the original contributors, and is subject to the original license terms described in the LICENSE file.

## How are open-source projects structured in ASAM?

ASAM recognizes several hosting modes:
- The product is developed within an ASAM project group and released under the ASAM GitHub organization.
  
    The declaration document specifies that:

        1. The software is a result of the project group’s activities.
        2. No project group member retains any rights.
        3. All required components are provided.
        4. The deliverable is free from malware.
        5. The deliverable is relevant for ASAM standardization work.

- The product is handed over to an ASAM project group for continued development(modification/extension) and jointly released via the ASAM marketplace.
  
     The declaration document specifies that:

        1. The software is a result of the project group’s activities.
        2. No project group member retains any rights.
        3. For third-party components (select applicable items):
            3.a The deliverable is free from third-party rights.
            3.b All third-party components are open-source.
            3.c All third-party rights have been transferred to ASAM.
        7. All required components are provided.
        8. The deliverable is free from malware.
        9. The deliverable is relevant for ASAM standardization work.
  
- The product is transferred to ASAM for direct publication, with no modifications, as an ASAM product on the ASAM marketplace.
  
    The transfer agreement specifies that:

      - ASAM is authorized to:
  
            1. Provide public access
            2. Distribute free copies
            3. Modify and/or integrate with other software
            4. Reject or delete the deliverable
            5. Sub-license the software
            6. Promote or advertise the deliverable
  
      - The third party guarantees:
  
            1. Compliance with ASAM’s licensing terms
            2. For third-party components (select applicable items):
                2.a The deliverable is free of third-party rights
                2.b All third-party components are open-source and comply with ASAM requirements
                2.c All third-party rights have been transferred to ASAM
            3. All necessary components are included
            4. The deliverable is free of malware
            5. The deliverable is relevant to ASAM standardization efforts
  
- The product is submitted directly to ASAM for publication as a third-party product, without any changes, on the ASAM marketplace (see [Marketplace Terms & Conditions](https://github.com/asam-ev/.github/blob/AsamDiegoSanchez-OSSP-ASAM-Structure/profile/MARKETPLACE_T%26Cs.md)).

![tp header](/doc/img/OpenSource_ASAM_Overview_Platform.png)

The ASAM office will consistently conduct a compliance check to ensure all requirements are met.

## How to officially [join ASAM](https://www.asam.net/about-asam/join-asam/) or the project

Before you fill out the [Membership Request Form](https://www.asam.net/index.php?eID=dumpFile&t=f&f=671&token=b37651b1609e8693188bbde1dafc4f229c18c2c8) we ask you to get familiar with the [ASAM Statutes](https://www.asam.net/index.php?eID=dumpFile&t=f&f=675&token=5a112bf0f7638cbfd647f89b89869af94e212762) and the [Regulation of Fees](https://www.asam.net/index.php?eID=dumpFile&t=f&f=673&token=1321eb0a4e6cfb99112f61648e411520f83a8d01). If you have questions when determining your member class, please check the FAQs below or contact us at info@asam.net.

After turning in your Membership Request Form, the ASAM Office will forward your application to the Board of Directors for approval. Upon decision of acceptance, the ASAM Office welcomes you and guides you through the server registration process. We also provide all relevant information (e. g. guidelines) and answer any questions you may have. Our goal is to inspire you to become an active member of the community so you can take the full advantage of your membership. 

## :bulb: Asking Questions

See our [Project Guide](https://asam-ev.github.io/asam-project-guide/asamprojectguide/latest/compendium/Development.html).

and also our [Anti-Trust Reminder](https://www.asam.net/index.php?eID=dumpFile&t=f&f=2496&token=90723c0e1dd4dc7000dd1bd362597c043ce9ecaf)

Or **contact our office: info@asam.net**

## :white_check_mark: Licensing

This project uses the MPL-2.0 License (as found in the [LICENSE file](https://github.com/asam-ev/.github/blob/AsamDiegoSanchez-OSSP-ASAM-Structure/profile/LICENSE.md)).

The license tells you what rights you have as a developer, provided by the copyright holder. It is important that the contributor fully understands the licensing rights and agrees to them. Sometimes the copyright holder isn’t the contributor, such as when the contributor is doing work on behalf of a company.

## :medal_sports: Developer Certification of Origin (DCO)

To make a good faith effort to ensure licensing criteria are met, this project requires the Developer Certificate of Origin (DCO) process to be followed.
The DCO is an attestation attached to every contribution made by every developer.
In the commit message of the contribution, (described more fully [here](#Usage-of-DCO-Sign-Off)), the developer simply adds a "Signed-off-by" statement and thereby agrees to the DCO.
When a developer submits a patch, it is a commitment that the contributor has the right to submit the patch per the license.
The DCO agreement is shown below and online at [developercertificate.org](https://developercertificate.org/).

> **Developer's Certificate of Origin 1.1**
>
>By making a contribution to this project, I certify that:
>
>(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or
>
>(b) The contribution is based upon previous work that, to the
    best of my knowledge, is covered under an appropriate open
    source license and I have the right under that license to
    submit that work with modifications, whether created in whole
    or in part by me, under the same open source license (unless
    I am permitted to submit under a different license), as
    Indicated in the file; or
>
>(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.
>
>(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including
    all personal information I submit with it, including my
    sign-off) is maintained indefinitely and may be redistributed
    consistent with this project or the open source license(s)
    involved.

### Usage of DCO Sign-Off

The DCO requires a sign-off message in the following format to appear on each commit in the pull request:

`Signed-off-by: Firstname Lastname <email@address.com> <comment>`

The DCO text can either be manually added to your commit body, or you can add either `-s` or `--signoff` to your usual Git commit commands.
If you forget to add the sign-off you can also amend a previous commit with the sign-off by running git commit `--amend -s`.
You can add sign-offs to multiple commits (including commits originally authored by others, if you are authorized to do so) using `git rebase --signoff`.
If you’ve pushed your changes to GitHub already you’ll need to force push your branch after this with `git push --force-with-lease`.
If you want to be reminded to add the sign-off for commits in your repository, you can add the following commit-message git hook to your repository:

```bash
#!/bin/sh
#
# Check for DCO/Signed-off-by in message
#

if ! grep -q "^Signed-off-by: " "$1"
then
  echo "Aborting commit: Commit message is not signed off" >&2
  exit 1
fi
```

Placing this script into a file called `.git/hooks/commit-msg` and making it executable (e.g. using `chmod a+x .git/hooks/commit-msg` on unixoid operating systems) will prevent commits without a sign-off.


## :mag: Implement changes

Feature additions and bug fixes from the community are very welcome.
Therefore, feel free not only to report an issue but also to work on a solution right away.
In order to implement changes, you can:

- fork the repository.
- request access to the contributors group. Then you can make your changes directly in this repository.

For both ways, the following workflow applies:

1. Open an issue.
2. Create a branch.
3. Create a draft pull request.
4. Convert the draft pull request into a 'real' pull request.

Labels are given for each step as described in the [ASAM contribution workflow](https://asam-ev.github.io/asam-project-guide/asamprojectguide/latest/compendium/Development/contribution.html).
The steps are further described in the following.

### :inbox_tray: Open an issue

Before [creating an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue), check if you are using the latest version of the project.

The first step is to identify and describe a bug or feature, or place a question.
Open a new issue in the respective project GitHub repository with the respective template for a bug or a feature.

- **Do not open a duplicate issue!** Search through existing issues to see if your issue has previously been reported. If your issue exists, comment with any additional information you have.

- **Prefer using [reactions](https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/)**, not comments, if you simply want to "+1" an existing issue.

- **Fully complete the provided issue template.** The templates requests all the information we need to quickly and efficiently address your issue. Be clear, concise, and descriptive. Provide as much information as you can.

- **Use [GitHub-flavored Markdown](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).** Especially put code blocks and console outputs in backticks (`). This improves readability.

- **Use Labels to categorize the issues.** Please check the official [ASAM issue guideline](https://asam-ev.github.io/asam-project-guide/asamprojectguide/latest/compendium/Development/contribute_with_issues.html).

In short, **provide a ticket that you would like to receive**.

### Create a branch

Create a new branch where you can start working on the issue.
You can use the link on the right side in the issue ("Development: Create a branch for this issue") to automatically create a new branch for the issue.

In order to create a branch, either fork the repository or request access to the contributors group.

### :repeat: Create a draft pull request

Before [forking the repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests) for non-trivial changes, it is usually best to first open an issue to discuss the changes, or discuss your intended approach for solving the problem in the comments for an existing issue.

*Note: All contributions will be licensed under the project's license.*

- **Smaller is better.** Submit **one** pull request per bug fix or feature. A pull request should contain isolated changes pertaining to a single bug fix or feature implementation. **Do not** refactor or reformat code that is unrelated to your change. It is better to **submit many small pull requests** rather than a single large one.

- **Coordinate bigger changes.** For large and non-trivial changes, open an issue to discuss a strategy with the maintainers.

- **Follow existing coding style and conventions.** Keep your code consistent with the style, formatting, and conventions in the rest of the code base. When possible, these will be enforced with a linter. Consistency makes it easier to review and modify in the future.

- When writing comments, use properly constructed sentences, including punctuation.

- Use spaces, not tabs.

- After creating the branch, commit your first changes. Follow the signing instructions for commits (DCO) [above](#Usage-of-DCO-Sign-Off)).
- Create a draft pull request and fill it out accordingly.
Be sure to link the issue you created earlier in the pull request.
- In the bottom, you can select to either submit as a pull request or as a draft pull request.
- Use a draft pull request first, so the community can already see the ongoing work.
- In this stage, the review from the project group and the service provider takes place.

Also, the CI pipeline will run for every commit, so you can continuously check your work.

### Convert into 'real' pull request

Once you are done with your changes and all reviews took place, [convert the draft to a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request).

By this, the change control board (CCB) knows that you are done with your work and that the pull request is ready for review and merge.

The CCB is a subgroup of experts from the project and responsible for internal alignment of topics, release management and approval/review of pull requests:
- Issue and MR/PR review
- Classification of issues
- Assignment of issues to solution developer(s)
- Milestone monitoring and planning
- Ensure alignment of individual Subgroup topics
- Release management

## :memo: Writing Commit Messages

Please [write a great commit message](https://chris.beams.io/posts/git-commit/).

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line (example: "Fix networking issue")
6. Wrap the body at about 72 characters

```
[TAG] Short summary of changes in 50 chars or less

Add a more detailed explanation here, if necessary. Possibly give
some background about the issue, etc. The body of the
commit message can be several paragraphs. Further paragraphs come
after blank lines and please do proper word-wrap.

Wrap it to about 72 characters or so. In some contexts,
the first line is treated as the subject of the commit and the
rest of the text as the body. The blank line separating the summary
from the body is critical (unless you omit the body entirely);
various tools like `log`, `shortlog` and `rebase` can get confused
if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how or what. The code explains
how or what. Reviewers and your future self can read the patch,
but might not understand why a particular solution was implemented.
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

 - Bullet points are okay, too

 - A hyphen or asterisk should be used for the bullet, preceded
   by a single space, with blank lines in between

Note the fixed or relevant GitHub issues at the end:

Resolves: #123
See also: #456, #789
```
