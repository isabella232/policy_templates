# Flexera CMP Policy Templates

This repository contains a library of open source Flexera CMP Policy Templates to provide governance via automation across Cost, Security, Operational, and Compliance categories.  All contributions are shared under the MIT license.

Please contact sales@flexera.com to learn more.

## Released Policy Templates

---

Categories

- [Cost](#cost)
- [Security](#security)
- [Compliance](#compliance)
- [Operational](#operational)
- [SaaS Management](#saas-management)

Reference

- [Policy Data Sets](#policy-data-sets)

---

### Cost

#### Multi-cloud

- [Budget Alerts](./cost/budget_alerts/)
- [Budget Alerts by Cloud Account](./cost/budget_alerts_by_account/)
- [Cheaper Regions](./cost/cheaper_regions/)
- [Cloud Cost Anomaly](./cost/cloud_cost_anomalies/)
- [Downsize Instances](./cost/downsize_instance/)
- [Inefficient Instance Utilization using RightLink](./cost/rightlink_rightsize)
- [Old Snapshots](./cost/volumes/old_snapshots/)
- [Running Instance Count Anomaly](./cost/instance_anomaly/)
- [Unattached IP Addresses](./cost/unattached_addresses/)
- [Unattached Volumes](./cost/volumes/unattached_volumes/)
- [Schedule Instances](./cost/schedule_instances/)
- [Scheduled Report](./cost/scheduled_reports/)
- [Scheduled Report with Estimates](./cost/scheduled_reports_with_estimates/)
- [Scheduled Report with Markups & Markdowns](./cost/scheduled_report_markupsdowns/)
- [Superseded Instances](./cost/superseded_instance/)
- [Superseded Instance Remediation](./cost/superseded_instance_remediation/)
- [Terminate Instances with End Date](./cost/terminate_policy/)

##### Forecasting

- [Cloud Spend Forecast - Moving Average](./cost/forecasting/moving_average/)
- [Cloud Spend Forecast - Straight-Line (Linear Regression Model)](./cost/forecasting/straight_line_forecast/linear_regression/)
- [Cloud Spend Forecast - Straight-Line (Simple Model)](./cost/forecasting/straight_line_forecast/simple/)
- [Vendor Commitment Forecast](./cost/forecasting/commitment_forecast/)

#### AWS

##### Credential Setup

- [Read Only CFT](./cost/aws/FlexeraReadOnlyPolicy.template)

##### Compute

- [AWS Burstable Instance CloudWatch Utilization](./cost/aws/burstable_instance_cloudwatch_credit_utilization/)
- [AWS Expiring Reserved Instances](./cost/aws/reserved_instances/expiration/)
- [AWS Idle Compute Instances](./cost/aws/idle_compute_instances/)
- [AWS Inefficient Instance Utilization using CloudWatch](./cost/aws/instance_cloudwatch_utilization/)
- [AWS Reserved Instances Utilization](./cost/aws/reserved_instances/utilization/)
- [AWS Reserved Instance Reservation Coverage](./cost/aws/reserved_instances/coverage/)
- [AWS Reserved Instances Report by Billing Center](./cost/aws/reserved_instances/report_by_bc)
- [AWS Reserved Instance Recommendations](./cost/aws/reserved_instances/recommendations)
- [AWS Savings Plan Recommendations](./cost/aws/savings_plan/recommendations)
- [AWS Savings Plan Utilization](./cost/aws/savings_plan/utilization)
- [AWS Savings Realized from Reservations](./cost/aws/savings_realized)
- [AWS Schedule Instance](./cost/aws/schedule_instance/)
- [AWS Unused IP Addresses](./cost/aws/unused_ip_addresses)

##### Database

- [AWS Unused RDS Instances](./cost/aws/unused_rds/)
- [AWS RDS Instances RightSizing](./cost/aws/rds_instance_cloudwatch_utilization)
- [AWS RDS Instances License Information](./cost/aws/rds_instance_license_info)

##### Load Balancers

- [AWS Delete Unused Elastic Load Balancers (CLB)](./cost/aws/elb/clb_unused/)

##### Storage

- [AWS Bucket Size Check](./cost/aws/s3_bucket_size/)
- [AWS Unused Volumes](./cost/aws/unused_volumes)
- [AWS S3 Buckets without Server Access Logging](./security/storage/aws/s3_buckets_without_server_access_logging/)
- [AWS Object Storage Optimization](./cost/aws/object_storage_optimization/)
- [AWS Old Snapshots](./cost/aws/old_snapshots/)
- [AWS S3 Bucket Intelligent Tiering Check](./cost/aws/s3_storage_policy/)

#### Azure

##### Compute

- [Azure Hybrid Use Benefit](./cost/azure/hybrid_use_benefit/)
- [Azure Hybrid Use Benefit for Linux](./cost/azure/hybrid_use_benefit_linux/)
- [Azure Hybrid Use Benefit for SQL](./cost/azure/hybrid_use_benefit_sql/)
- [Azure Idle Compute Instances](./cost/azure/idle_compute_instances/)
- [Azure Inefficient Instance Utilization using Log Analytics](./cost/azure/instances_log_analytics_utilization/)
- [Azure Expiring Reserved Instances](./cost/azure/reserved_instances/expiration)
- [Azure Reserved Instance Utilization](./cost/azure/reserved_instances/utilization/)
- [Azure Reserved Instance Recommendations](./cost/azure/reserved_instances/mca_recommendations)
- [Azure Unused IP Addresses](./cost/azure/unused_ip_addresses)
- [Azure Savings Realized from Reservations](./cost/azure/savings_realized)
- [Azure Schedule Instance](./cost/azure/schedule_instance/)

##### Database

- [Azure Rightsize SQL Instances](./cost/azure/rightsize_sql_instances/)
- [Azure Unused SQL Databases](./cost/azure/unused_sql_databases/)

##### Storage

- [Azure Blob Storage Optimization](./cost/azure/object_storage_optimization/)
- [Azure Old Snapshots](./cost/azure/old_snapshots/)
- [Azure Unused Volumes](./cost/azure/unattached_volumes)
- [Azure Storage Accounts without Lifecycle Management Policies](./cost/azure/storage_account_lifecycle_management/)

#### Google

##### Compute

- [Google Inefficient Instance Utilization using StackDriver](./cost/google/instances_stackdriver_utilization/)
- [Google Committed Use Discount (CUD)](./cost/google/cud_report/)
- [Google Committed Use Discount Recommender (CUD)](./cost/google/cud_recommendations/)
- [Google Idle Compute Instances](./cost/google/idle_compute_instances/)
- [Google Expiring Committed Use Discount (CUD)](./cost/google/cud_expiration/)
- [Google Schedule Instance](./cost/google/schedule_instance/)
- [Google Idle VM Recommender](./cost/google/idle_vm_recommendations)

##### Database

- [Google Unused CloudSQL Instances](./cost/google/unused_cloudsql_instances)
- [Google Rightsize CloudSQL Instances](./cost/google/cloudsql_rightsizing/)
- [Google Cloud SQL Idle Instance Recommender](./cost/google/cloud_sql_idle_instance_recommendations)

##### Storage

- [Google Object Storage Optimization](./cost/google/object_storage_optimization/)
- [Google Old Snapshots](./cost/google/old_snapshots/)
- [Google Unused Volumes](./cost/google/unattached_volumes/)
- [Google Idle Persistent Disk Recommender](./cost/google/idle_persistent_disk_recommendations)

##### Native Recommendations

- [Google Recommender Policy](./cost/google/recommender/)

##### Other

- [Google Unutilized IP Addresses](./cost/google/unutilized_ip_addresses/)
- [Google Idle IP Address Recommender](./cost/google/idle_ip_address_recommendations)

### Security

#### Multi-cloud

- [Security Group: ICMP Enabled](./security/security_groups/icmp_enabled/)
- [Security Group: Rules Without Description](./security/security_groups/rules_without_descriptions/)
- [Security Group: High Open Ports](./security/security_groups/high_open_ports/)
- [Security Groups With Ports Open To The World](./security/security_groups/world_open_ports)

#### AWS

##### IAM

###### CIS Policies

- [AWS No Root Access Keys](./security/aws/iam_no_root_access_keys/)
- [AWS MFA Enabled For Root User](./security/aws/iam_mfa_enabled_for_root/)
- [AWS Hardware MFA Enabled For Root User](./security/aws/iam_hwmfa_enabled_for_root/)
- [AWS MFA Enabled For IAM Users](./security/aws/iam_mfa_enabled_for_iam_users/)
- [AWS Minimum Password Length](./security/aws/iam_min_password_length/)
- [AWS Prevent Password Reuse](./security/aws/iam_prevent_password_reuse/)
- [AWS Disable Credentials Unused For 45+ Days](./security/aws/iam_disable_45_day_creds/)
- [AWS Ensure One Active Key Per IAM User](./security/aws/iam_one_active_key_per_user/)
- [AWS Rotate Access Keys](./security/aws/iam_rotate_access_keys/)
- [AWS Ensure IAM Users Receive Permissions Only Through Groups](./security/aws/iam_users_perms_via_groups_only/)
- [AWS Access Analyzer Enabled](./security/aws/iam_access_analyzer_enabled/)
- [AWS Support Role Created](./security/aws/iam_support_role_created/)
- [AWS Report Attached Admin IAM Policies](./security/aws/iam_no_admin_iam_policies_attached/)
- [AWS Expired SSL Certs](./security/aws/iam_expired_ssl_certs/)

##### Database

- [AWS Publicly Accessible RDS Instances](./security/aws/rds_publicly_accessible/)

###### CIS Policies

- [AWS Unencrypted RDS Instances](./security/aws/rds_unencrypted/)

##### KMS

###### CIS Policies

- [AWS Ensure Rotation For Customer Master Keys (CMKs) Is Enabled](./security/aws/kms_rotation/)

##### Storage

- [AWS EBS Ensure Encryption By Default](./security/aws/ebs_ensure_encryption_default/)
- [AWS Open Buckets](./security/storage/aws/public_buckets/)
- [AWS Unencrypted Volumes](./security/aws/ebs_unencrypted_volumes/)

###### CIS Policies

- [AWS EBS Ensure Encryption By Default](./security/aws/ebs_ensure_encryption_default/)
- [AWS S3 Ensure Buckets Block Public Access](./security/aws/s3_ensure_buckets_block_public_access/)
- [AWS S3 Ensure MFA Delete Enabled](./security/aws/s3_ensure_mfa_delete_enabled/)
- [AWS Unencrypted S3 Buckets](./security/aws/unencrypted_s3_buckets/)
- [AWS S3 Buckets Deny HTTP](./security/aws/s3_buckets_deny_http/)

##### Logging

###### CIS Policies

- [AWS Ensure Log File Validation Enabled For All CloudTrails](./security/aws/log_file_validation_enabled/)
- [AWS Ensure CloudTrail Enabled In All Regions](./security/aws/log_ensure_cloudtrail_multiregion/)

##### Load Balancers

- [AWS Internet-facing ELBs & ALBs](./security/aws/loadbalancer_internet_facing/)
- [AWS Unencrypted ELB Listeners (CLB)](./security/aws/clb_unencrypted/)
- [AWS Unencrypted ELB Listeners (ALB/NLB)](./security/aws/elb_unencrypted/)

##### Logging

###### CIS Policies

- [AWS Ensure Object-level Events Logging Enabled For CloudTrails](./security/aws/log_ensure_cloudtrail_bucket_object_logging/)
- [AWS Ensure CloudTrail Logs Encrypted At Rest](./security/aws/log_ensure_cloudtrail_encrypted/)
- [AWS Ensure CloudTrail S3 Buckets Have Access Logging](./security/aws/log_ensure_cloudtrail_bucket_access_logging/)
- [AWS Ensure CloudTrail Integrated With Cloudwatch](./security/aws/log_cloudtrail_cloudwatch_integrated/)
- [AWS Ensure AWS Config Enabled In All Regions](./security/aws/aws_config_enabled/)

#### VPC

- [AWS VPC's without FlowLogs Enabled](./security/aws/vpcs_without_flow_logs_enabled/)

#### Azure

- [Azure Resources with public IP address](./security/azure/resources_with_public_ip_address)

##### Compute

###### CIS Policies

- [Azure Ensure Log Analytics Auto-Provisioning](./security/azure/log_analytics_autoprovision/)

##### IAM

###### CIS Policies

- [Azure Guest Users Audit](./security/azure/guest_users/)

##### Database

- [Azure Publicly Accessible Managed SQL Instance](./security/azure/sql_publicly_accessible_managed_instance/)

###### CIS Policies

- [Azure Ensure MySQL Flexible Servers Use Secure TLS](./security/azure/mysql_tls_version/)
- [Azure Ensure MySQL Servers Enforce SSL Connections](./security/azure/mysql_ssl/)
- [Azure Ensure PostgreSQL Servers Infrastructure Encryption](./security/azure/pg_infra_encryption/)
- [Azure Ensure SQL Server Auditing Enabled](./security/azure/sql_server_auditing/)
- [Azure Ensure SQL Server AD Admin Configured](./security/azure/sql_ad_admin/)
- [Azure Ensure SQL Server VA Email Notifications](./security/azure/sql_server_va_emails/)
- [Azure Ensure SQL Server VA Notify Admins/Subscription Owners](./security/azure/sql_server_va_admins/)
- [Azure Ensure SQL Server Vulnerability Assessment (VA) Enabled](./security/azure/sql_server_va/)

##### Web Apps

- [Azure Web App Minimum TLS Version](./security/azure/webapp_tls_version_support/)

##### Storage

- [Azure Storage Accounts Without HTTPs Enforced](./security/storage/azure/storage_account_https_enabled/)

###### CIS Policies

- [Azure Ensure Storage Account Default Network Access Set To Deny](./security/azure/storage_network_deny/)
- [Azure Ensure Blob Containers Set To Private](./security/azure/private_blob_containers/)
- [Azure Ensure Storage Logging Enabled For Blob Service](./security/azure/blob_storage_logging/)
- [Azure Ensure Storage Logging Enabled For Queue Service](./security/azure/queue_storage_logging/)
- [Azure Ensure Storage Logging Enabled For Table Service](./security/azure/table_storage_logging/)
- [Azure Ensure Secure Transfer Required](./security/azure/secure_transfer_required/)
- [Azure Ensure Soft Delete Enabled For Azure Storage](./security/azure/storage_soft_delete/)
- [Azure Ensure Storage Accounts Require Secure TLS Version](./security/azure/storage_tls_version/)
- [Azure Ensure Trusted Microsoft Services Enabled](./security/azure/storage_trusted_services/)

##### Security

###### CIS Policies

- [Azure Ensure Owners Receive Security Alerts](./security/azure/security_alert_owners/)
- [Azure Ensure High Severity Alerts](./security/azure/high_severity_alerts/)
- [Azure Ensure Security Contact Email](./security/azure/security_contact_email/)
- [Azure Network Security Groups With Inbound RDP Open](./security/azure/restrict_rdp_internet/)
- [Azure Network Security Groups With Inbound SSH Open](./security/azure/restrict_ssh_internet/)

#### Google

- [Google Open Buckets](./security/storage/google/public_buckets/)

### Compliance

#### Flexera

- [Flexera IAM Explicit User Roles](./compliance/flexera/iam_explicit_user_roles/)

#### Multi-cloud

- [Billing Center Access](./compliance/billing_center_access_report/)
- [Untagged Resources](./compliance/tags/tag_checker)
- [Unapproved Instance Types](./compliance/unapproved_instance_types/)
- [Disallowed Cloud Images](./compliance/disallowed_images/)

#### AWS

- [AWS Disallowed Regions](./compliance/aws/disallowed_regions/)
- [AWS Unused ECS Clusters](./compliance/aws/ecs_unused/)
- [AWS EC2 Instances not running FlexNet Inventory Agent](./compliance/aws/instances_without_fnm_agent/)
- [AWS Long-stopped Instances](./compliance/aws/long_stopped_instances/)
- [AWS Untagged Resources](./compliance/aws/untagged_resources/)
- [AWS Service Control Policy Audit](./compliance/aws/scp_audit/)
- [AWS IAM Role Audit](./compliance/aws/iam_role_audit/)

#### Azure

- [Azure AHUB Utilization with Manual Entry](./compliance/azure/ahub_manual/)
- [Azure Disallowed Regions](./compliance/azure/azure_disallowed_regions)
- [Azure Instances not running FlexNet Inventory Agent](./compliance/azure/instances_without_fnm_agent/)
- [Azure Long Stopped Instances](./compliance/azure/azure_long_stopped_instances)
- [Azure Policy Audit](./compliance/azure/azure_policy_audit)
- [Azure Regulatory Compliance](./compliance/azure/compliance_score/)
- [Azure Subscription Access](./compliance/azure/subscription_access/)
- [Azure Tag Resources with Resource Group Name](./compliance/tags/azure_rg_tags)
- [Azure Untagged Resources](./compliance/azure/azure_untagged_resources)

#### Google

- [Google Long-Stopped Instances](./compliance/google/long_stopped_instances)
- [Google Unlabeled Resources](./compliance/google/unlabeled_resources)

#### ITAM/FNMS

- [FlexNet Manager Licenses At Risk](./compliance/fnms/fnms_licenses_at_risk/)
- [FlexNet Manager Low Available Licenses](./compliance/fnms/fnms_low_licenses_available)
- [ITAM Missing Active Machines](./compliance/fnms/missing_active_machines/)
- [ITAM Ignored Recent Inventory Dates](./compliance/fnms/ignored_recent_inventory_dates/)
- [ITAM Overused Licenses](./compliance/fnms/overused_licenses)
- [ITAM VMs Missing Host ID](./compliance/fnms/vms_missing_hostid)

#### Github

- [GitHub.com Available Seats](./compliance/github/available_seats/)
- [GitHub.com Unpermitted Outside Collaborators](./compliance/github/outside_collaborators/)
- [GitHub.com Unpermitted Repository Names](./compliance/github/repository_naming/)
- [GitHub.com Unpermitted Top-Level Teams](./compliance/github/toplevel_teams/)
- [GitHub.com Unpermitted Sized Repositories](./compliance/github/repository_size/)
- [GitHub.com Repository Branches without Protection](./compliance/github/repository_branch_protection/)
- [GitHub.com Repositories without Admin Team](./compliance/github/repository_admin_team/)

#### Other

- [Policy Update Notification](./compliance/policy_update_notification/)

### Operational

#### Multi-cloud

- [Application Migration Recommendations](./operational/compute_instance_migration/)
- [No Recent Snapshots](./operational/snapshots/)
- [Stranded Servers](./operational/stranded_servers/)
- [NetFlow Top Talkers](./operational/azure/network_flow)
- [Applied Policy Error Notification](./operational/applied_policy_error_notification/)
- [Bill Processing Error Notification](./operational/bill_processing_errors_notification/)

#### AWS

- [AWS Cloud Credentials Rotation](./operational/cloud_credentials/aws)
- [AWS RDS Backup Settings](./operational/dbaas/aws/rds_backup)
- [AWS Subnet Name Tag Sync](./operational/aws/subnet_name_sync)
- [AWS VPC Name Tag Sync](./operational/aws/vpc_name_sync)
- [AWS Long Running Instances](./operational/aws/long_running_instances/)
- [AWS Instance Scheduled Events](./operational/aws/instance_scheduled_events)
- [AWS Lambda Functions with high error rate](./operational/aws/lambda_functions_with_high_error_rate/)
- [AWS Tag Cardinality Report](./operational/aws/tag_cardinality/)
- [AWS Usage Report - Number of Instance Hours Used](./operational/aws/total_instance_hours/)
- [AWS Usage Report - Number of Instance vCPUs Used](./operational/aws/total_instance_vcpus/)
- [AWS Usage Forecast - Number of Instance Hours Used](./operational/aws/total_instance_hours_forecast/)
- [AWS Usage Forecast - Number of Instance vCPUs Used](./operational/aws/total_instance_vcpus_forecast/)

#### Azure

- [Azure VMs Not Using Managed Disks](./operational/azure/vms_without_managed_disks/)
- [Azure Expiring Certificates](./operational/azure/azure_certificates/)
- [Azure Migrate Integration](./operational/azure/azure_migrate)
- [AzureAD Group Sync](./operational/azure/azuread_group_sync/)
- [Azure Sync Tags with Optima](./operational/azure/sync_tags_with_optima/)
- [Azure SQL Databases without Elastic Pools](./operational/azure/azure_sql_using_elastic_pool/)
- [Azure Tag Cardinality Report](./operational/azure/tag_cardinality/)

#### VMWare

- [VMWare Instance Tag Sync](./operational/vmware/instance_tag_sync)

#### Other

- [Schedule FlexNet Manager Report](./operational/fnms/schedule_fnms_reports/)

### SaaS Management

- [Okta Inactive Users](./saas/okta/inactive_users)
- [ServiceNow Inactive Approvers](./saas/servicenow/inactive_approvers)
- [Office 365 Security Alerts](./saas/office365/security_alerts)
- [SaaS Manager - Renewal Reminder](./saas/fsm/renewal_reminder)
- [SaaS Manager - User Status Change](./saas/fsm/user_status_change)
- [SaaS Manager - Suspicious Users](./saas/fsm/suspicious_users)
- [SaaS Manager - Unsanctioned Spend](./saas/fsm/unsanctioned_spend)
- [SaaS Manager - Redundant Apps](./saas/fsm/redundant_apps)
- [SaaS Manager - Inactive Users by Department](./saas/fsm/inactive_users_by_dept)
- [SaaS Manager - Inactive Users for Integrated Applications](./saas/fsm/inactive_users_for_integrated_apps)
- [SaaS Manager - Duplicate User Accounts](./saas/fsm/duplicate_users)
- [SaaS Manager - Unsanctioned Applications with Existing Contract](./saas/fsm/unsanctioned_apps_with_contract)
- [SaaS Manager - SaaS App User Report by Category](./saas/fsm/users_by_category)

### Policy Data Sets

- [AWS Regions](./data/aws/regions.json)
- [AWS Instance Types](./data/aws/instance_types.json)
- [Azure Instance Types](./data/azure/instance_types.json)
- [Google Instance Types](./data/google/instance_types.json)
- [Currency Reference](./cost/scheduled_reports/currency_reference.json)
- [Azure SQL Service Tier Types](./data/azure/sql_service_tier_types.json)
- [TZ database Timezone List](./data/tz_database/timezones_list.json)

## Instructions to upload policy templates to Flexera CMP Policies

- The policy templates in the repo are the files that have a .pt extension.
- Select the desired policy template, click on the “Raw” button, and then right-click and choose “Save As” to save the file to your computer.
- To upload the template to your account, navigate over to the Templates page in the left nav bar in [Governance](https://governance.rightscale.com). Ensure you have the role to access policy management in RightScale. Learn More about [Policy Access Control](https://docs.flexera.com/flexera/EN/Automation/AutomationGS.htm#how-policies-work-access-control).
- Click the “Upload Policy Template” button in the account you wish to test the policy and follow the instructions to upload the template you just downloaded.

## Policy Template Documentation

- [Getting Started](https://docs.flexera.com/flexera/EN/Automation/AutomationGS.htm)
- [Reference Documentation](https://docs.flexera.com/flexera/EN/Automation/AutomationRefInfo.htm#automationrefinfo_1419216867_1009635)
- [Policy Template Language](https://docs.flexera.com/flexera/EN/Automation/PTL.htm#automationrefinfo_1419216867_1122815)
- [Markdown Editor](https://jbt.github.io/markdown-editor/) - Use this to test Markdown Syntax
- [Libraries](./libraries/README.md)
- [README GUIDELINE](./README_GUIDELINE.md)

## Getting Help

Support for these policy templates will be provided though GitHub Issues and the Flexera Community.
Visit [Flexera Community](https://community.flexera.com) to join!

### Opening an Issue

Github issues contain a template for three types of requests(Bugs, New Features to an existing Policy Template, New Policy Template Request)

- Bugs: Any issue you are having with an existing policy template not functioning correctly, this does not include missing features, or actions.
- New Feature Request: Any feature(Field, Action, Link, Output, etc) that are to be added to an existing policy template.
- New Policy Template Request: Request for a new policy template.

### Troubleshooting Danger Locally

- You can test against a pull request via: `bundle exec danger pr https://github.com/flexera-public/policy_templates/pull/73 --pry`
- [Danger Troubleshooting](http://danger.systems/guides/troubleshooting.html)
