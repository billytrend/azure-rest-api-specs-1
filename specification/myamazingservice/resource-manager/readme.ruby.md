## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_myamazingservice
package-version: 34131431
azure-arm: true
```

### Tag: package-34131431 and ruby

These settings apply only when `--tag=package-34131431 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-34131431' && $(ruby)
namespace: Microsoft.Lol
output-folder: $(ruby-sdks-folder)/myamazingservice
```
