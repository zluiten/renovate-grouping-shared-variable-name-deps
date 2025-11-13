# discussions/39288

Reproduction for [Renovate discussion 39288](https://github.com/renovatebot/renovate/discussions/39288).

## Current behavior

Currently, Renovate does not group dependencies that are already (internally) grouped by sharedVariableName even if
they are in the same packageRule combined with a package update that isn't included in the sharedVariableName.

## Expected behavior

I expect the configuration in the renovate.json about grouping dependencies to take precedence over the internal 
grouping.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/39288
