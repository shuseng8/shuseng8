# Open source

Contributions to other people's projects, grouped by status. Status comes from GitHub and is updated when a PR changes state. An open PR is not an accepted one.

Last updated: 2026-11-26

**7 merged, 9 open.**

## Merged

| Project | PR | What it does |
| --- | --- | --- |
| MAAS Terraform Modules | [#132](https://github.com/canonical/maas-terraform-modules/pull/132) | Updates the Testflinger action and turns on its built-in retries for flaky bare-metal test runs. Merged Nov 26, 2026. |
| Keycloak | [#55210](https://github.com/keycloak/keycloak/pull/55210) | Records the ID of a new organization group in its create admin event path, so the event can be found under the group. Merged Nov 26, 2026. |
| Terraform AWS Provider | [#51220](https://github.com/hashicorp/terraform-provider-aws/pull/51220) | Adds the T8i and T9g instance types to the burstable instance family lists in the EC2 and ECS documentation. Merged Nov 24, 2026. |
| Spring WS | [#1990](https://github.com/spring-projects/spring-ws/pull/1990) | Excludes web fonts from the published javadoc jars, shrinking the spring-xml javadoc jar from 4.2 MB to 291 KB. Merged Nov 23, 2026. |
| OpenSearch Migrations | [#3535](https://github.com/opensearch-project/opensearch-migrations/pull/3535) | Stops using the GNU-only `tac` command to order CloudFormation events in `aws-bootstrap.sh`. Merged Nov 17, 2026. |
| Kestra | [#22414](https://github.com/kestra-io/kestra/pull/22414) | Shows Started filter dates in the Settings timezone instead of the browser timezone. Merged Nov 9, 2026. |
| Kestra | [#22395](https://github.com/kestra-io/kestra/pull/22395) | Adds a unit test for the NamespaceFilesEmpty empty state. Merged Nov 9, 2026. |

## Open

| Project | PR | What it does | State |
| --- | --- | --- | --- |
| Keycloak | [#54849](https://github.com/keycloak/keycloak/pull/54849) | Rejects empty or blank credential labels in the Account API and in the OTP and Passkey setup flows. | Approved by vaceksimon, needs a second approval. |
| OpenSearch Neural Search | [#2100](https://github.com/opensearch-project/neural-search/pull/2100) | Reports `hits.total` relation as `gte` only when the hybrid query hit count exceeds `track_total_hits`, matching Lucene's threshold. | Waiting for review. Two multi-node JDK21 integration tests failed on the latest run. |
| OpenSearch SQL | [#5955](https://github.com/opensearch-project/sql/pull/5955) | Accepts a single value in `mvindex` and date/time values in `split`. | Waiting for a maintainer to approve CI and add the bugFix label. |
| Spring Cloud AWS | [#1730](https://github.com/awspring/spring-cloud-aws/pull/1730) | Manages the `aws-crt` version alongside the AWS SDK version in the bill of materials. | Approved by klopfdreh, waiting for a maintainer to merge. |
| Spring Cloud AWS | [#1734](https://github.com/awspring/spring-cloud-aws/pull/1734) | Clarifies that the Kinesis binder's `shardIteratorType` applies only when a shard has no stored checkpoint, and that setting `TRIM_HORIZON` does not reset existing checkpoints. | Waiting for [#1685](https://github.com/awspring/spring-cloud-aws/pull/1685) to merge. |
| Spring LDAP | [#1951](https://github.com/spring-projects/spring-ldap/pull/1951) | Deprecates the DIGEST-MD5 authentication strategy, citing RFC 6331, and points to simple bind over TLS as the replacement. | Waiting for review. |
| Argo CD | [#31139](https://github.com/argoproj/argo-cd/pull/31139) | Automatically collapses the application status panel on short windows so more of the tree, network, or list view stays visible. | CI passed, CodeRabbit comments addressed, waiting for review. |
| NVIDIA aicr | [#4052](https://github.com/NVIDIA/aicr/pull/4052) | Pins the argocd, flux, and argocd-helm bundler READMEs with golden files (fix for [#4039](https://github.com/NVIDIA/aicr/issues/4039)). | CI passed. Reviewed by lockwobr; comment wording changes being addressed. |
| pgAdmin | [#10835](https://github.com/pgadmin-org/pgadmin4/pull/10835) | Remembers the last used folder per purpose in Desktop file dialogs. | Waiting for review. |
