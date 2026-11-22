# Rosenlund-Labs: default community health files

GitHub requires this repo to be public to supply defaults to the organization's repos. It holds only issue forms and a config file. It must never hold anything private.

- `.github/ISSUE_TEMPLATE/`: the forms every repo in the organization offers under "New issue", unless the repo has its own `ISSUE_TEMPLATE` folder (then none of these apply to it).
  - **Task (Binnacle can do it):** a change an agent can make and check. Add the `binnacle:ready` label by hand when its checklist is true.
  - **Decision or spec:** a question that needs a person, or work that needs a spec or plan first. Adds the `needs:me` label.
  - **Epic:** a goal made of several tickets.
  - **Chore (a person does it):** a setting, account or other work outside the repo. Adds the `needs:me` label.
  - **Bug:** something does not work as it should.

The standard behind these forms is in the private `rosenlund-labs` repo, `docs/standards/tickets.md`.

The `needs:me` label must exist in this repo and in every repo that uses the forms, or GitHub does not apply it.
