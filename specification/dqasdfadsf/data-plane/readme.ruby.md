## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_dqasdfadsf
package-version: 123
azure-arm: true
```

### Tag: package-123 and ruby

These settings apply only when `--tag=package-123 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-123' && $(ruby)
namespace: Microsoft.fasdf123
output-folder: $(ruby-sdks-folder)/dqasdfadsf
```
