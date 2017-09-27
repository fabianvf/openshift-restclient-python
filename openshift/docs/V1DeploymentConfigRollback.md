# V1DeploymentConfigRollback

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_version** | **str** | APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#resources | [optional] 
**kind** | **str** | Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the openshift.client submits requests to. Cannot be updated. In CamelCase. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds | [optional] 
**name** | **str** | Name of the deployment config that will be rolled back. | 
**spec** | [**V1DeploymentConfigRollbackSpec**](V1DeploymentConfigRollbackSpec.md) | Spec defines the options to rollback generation. | 
**updated_annotations** | **dict(str, str)** | UpdatedAnnotations is a set of new annotations that will be added in the deployment config. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


