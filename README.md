## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_null"></a> [null](#provider\_null) | 3.1.0 |
| <a name="provider_yandex"></a> [yandex](#provider\_yandex) | 0.61.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [null_resource.ansible-install](https://registry.terraform.io/providers/hashicorp/null/latest/docs/resources/resource) | resource |
| [yandex_compute_instance.vm-1](https://registry.terraform.io/providers/yandex-cloud/yandex/latest/docs/resources/compute_instance) | resource |
| [yandex_vpc_network.network-1](https://registry.terraform.io/providers/yandex-cloud/yandex/latest/docs/resources/vpc_network) | resource |
| [yandex_vpc_subnet.subnet-1](https://registry.terraform.io/providers/yandex-cloud/yandex/latest/docs/resources/vpc_subnet) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_cloud_id"></a> [cloud\_id](#input\_cloud\_id) | n/a | `string` | n/a | yes |
| <a name="input_folder_id"></a> [folder\_id](#input\_folder\_id) | n/a | `string` | n/a | yes |
| <a name="input_image_id"></a> [image\_id](#input\_image\_id) | n/a | `string` | n/a | yes |
| <a name="input_num"></a> [num](#input\_num) | n/a | `number` | n/a | yes |
| <a name="input_yc_token"></a> [yc\_token](#input\_yc\_token) | n/a | `string` | n/a | yes |
| <a name="input_zone"></a> [zone](#input\_zone) | n/a | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_external_ip_address_vm_1"></a> [external\_ip\_address\_vm\_1](#output\_external\_ip\_address\_vm\_1) | n/a |
| <a name="output_internal_ip_address_vm_1"></a> [internal\_ip\_address\_vm\_1](#output\_internal\_ip\_address\_vm\_1) | n/a |
