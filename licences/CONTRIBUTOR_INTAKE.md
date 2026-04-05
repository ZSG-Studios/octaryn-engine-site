# Octaryn Engine Contributor Intake

Octaryn Engine uses a verified Google Apps Script web app intake flow for
first-time substantive contributors.

Verified intake page:

https://zsg-studios.github.io/octaryn-engine-site/contribute.html

## Important

The intake app is public to access, but it verifies the contributor's GitHub
account through GitHub OAuth first. Submitted intake details are stored
privately in the private intake repo controlled by Zachary David Rose.

## What the intake flow does

- records your GitHub-account-based assent to the current project rules;
- confirms you reviewed the public summaries for the license, contribution
  rules, and assignment terms before starting the verified flow;
- confirms you understand Octaryn Engine is access-controlled and not open source;
- confirms you understand that only Zachary David Rose may distribute,
  commercialize, or otherwise release the project unless he separately
  authorizes otherwise in writing; and
- records your legal name and email address for contributor recordkeeping; and
- establishes the intake record maintainers check before reviewing a first
  substantive pull request.

The verified web app checks the real GitHub account through GitHub OAuth,
records the contributor details privately, and sends an approval email to the
maintainer before any private collaborator invite is sent.

## Contributor workflow

1. Open the public intake page and read the public summaries there before starting the verified flow.
2. Start the verified intake app from that page and sign in with the GitHub account you will use for contributions.
3. Complete the private intake form inside the verified flow.
4. Wait for maintainer approval.
5. If approved, accept the collaborator invites sent for `octaryn-core` and
   `octaryn-editor`.
6. Use the same GitHub account for later pull requests.
7. Open PRs normally using the PR template.

## Maintainer workflow

1. Check that the contributor completed the verified intake flow.
2. Use the emailed approval link to approve access.
3. Confirm the verified GitHub login matches the contributor account used for the PR.
4. Review and merge contributions under the repository's normal PR workflow.
