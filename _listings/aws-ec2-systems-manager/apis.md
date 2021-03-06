---
name: AWS EC2 Systems Manager
x-slug: aws-ec2-systems-manager
description: Amazon EC2 Systems Manager is a management service that helps you automatically
  collect software inventory, apply OS patches, create system images, and configure
  Windows and Linux operating systems. These capabilities help you define and track
  system configurations, prevent drift, and maintain software compliance of your EC2
  and on-premises configurations. By providing a management approach that is designed
  for the scale and agility of the cloud but extends into your on-premises data center,
  EC2 Systems Manager makes it easier for you to seamlessly bridge your existing infrastructure
  with AWS.EC2 Systems Manager is easy to use. Simply access EC2 Systems Manager from
  the EC2 Management Console, select the instances you want to manage, and define
  the management tasks you want to perform. EC2 Systems Manager is available now at
  no cost to manage both your EC2 and on-premises resources.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Inventory
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Systems Manager API - Get Inventory
  x-api-slug: actiongetinventory-get
  description: Query inventory information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/actiongetinventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/actiongetinventory-get-openapi.md
- name: AWS EC2 Systems Manager API - Get Inventory Schema
  x-api-slug: actiongetinventoryschema-get
  description: |-
    Return a list of inventory type names for the account, or return a list of attribute
       names for a specific Inventory item type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/actiongetinventoryschema-get-openapi.md
- name: AWS EC2 Systems Manager API - List Inventory Entries
  x-api-slug: actionlistinventoryentries-get
  description: A list of inventory items returned by the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/actionlistinventoryentries-get-openapi.md
- name: AWS EC2 Systems Manager API - Put Inventory
  x-api-slug: actionputinventory-get
  description: Bulk update custom inventory items on one more instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/actionputinventory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/inventory/master/_listings/aws-ec2-systems-manager/actionputinventory-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.container.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.systems.manager.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/ssm/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/systems-manager/faqs/
- type: x-getting-started
  url: http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/systems-manager.html
- type: x-website
  url: https://aws.amazon.com/ec2/systems-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---