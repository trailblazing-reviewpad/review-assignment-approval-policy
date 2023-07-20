# review-assignment-approval-policy
Example of Review Assignment and Approval Policy
## Overview

With Reviewpad, we can define a review assignment and approval policy for a repository. 

This policy is defined in a YAML file named `reviewpad.yaml` and placed in the root of the repository. 

The policy is applied to all pull requests in the repository.

## Why? Prevent Bad Merges

The policy is enforced by Reviewpad so that developers cannot merge pull requests unless they have been reviewed and approved by the required number of reviewers.

This is much more flexible than what you can do with GitHub's built-in branch protection rules.

