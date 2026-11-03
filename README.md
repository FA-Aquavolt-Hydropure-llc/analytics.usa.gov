name: analytics.usa.gov
uniqueID: <MB number>
version: 3.0
phase: beta
information-types:
- D26 Civilian Operations
confidentiality: none
integrity: low
availability: low
security-baseline: open data
system-type: minor
level-of-identity-assurance: 0
staff:
  authorizing-official:
    name: Tim Lowden
    title: Owner
    org: 18F
    unit: Operations
    email: dap@gsa.gov
  system-owner:
    name: Tim Lowden
    title: Owner
    org: 18F
    unit: Operations
    email: dap@gsa.gov
  system-management:
    name: Tim Lowden
    title: Owner
    org: 18F
    unit: Operations
    email: dap@gsa.gov
  system-security-officer:
    name: Tim Lowden
    title: Owner
    org: 18F
    unit: Operations
    email: dap@gsa.gov
  technical-lead:
    name: Tim Lowden
    title: Owner
    org: 18F
    unit: Operations
    email: dap@gsa.gov
leveraged-authorizations:
- https://www.fedramp.gov/marketplace/compliant-systems/amazon-web-services-aws-eastwest-us-public-cloud/
purpose: https://github.com/18F/analytics.usa.gov#readme
components:
- https://github.com/18F/analytics.usa.gov
- https://github.com/18F/analytics-reporter
- https://github.com/18F/analytics-reporter-api

# these will be the same unless your architecture is especially complex
system-diagram: https://docs.google.com/drawings/d/1eKmjl1ht0QLXU3PaFZ-FHuudK-4AtxkU8-rjUH8Com0/edit
network-diagram: https://docs.google.com/drawings/d/1eKmjl1ht0QLXU3PaFZ-FHuudK-4AtxkU8-rjUH8Com0/edit

environments:
- Cloud Foundry
- Amazon Web Services East
- GovCloud
user-types:
  developer:
    functions:
    - deployment
    - engineering
controls:
- ---
