# AWS::Kendra::DataSource ConfluenceAttachmentFieldMappingsList<a name="aws-properties-kendra-datasource-confluenceattachmentfieldmappingslist"></a>

A list of mappings between a Confluence data source and Amazon Kendra index fields\.

## Syntax<a name="aws-properties-kendra-datasource-confluenceattachmentfieldmappingslist-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-kendra-datasource-confluenceattachmentfieldmappingslist-syntax.json"></a>

```
{
  "[ConfluenceAttachmentFieldMappingsList](#cfn-kendra-datasource-confluenceattachmentfieldmappingslist-confluenceattachmentfieldmappingslist)" : [ ConfluenceAttachmentToIndexFieldMapping, ... ]
}
```

### YAML<a name="aws-properties-kendra-datasource-confluenceattachmentfieldmappingslist-syntax.yaml"></a>

```
  [ConfluenceAttachmentFieldMappingsList](#cfn-kendra-datasource-confluenceattachmentfieldmappingslist-confluenceattachmentfieldmappingslist): 
    - ConfluenceAttachmentToIndexFieldMapping
```

## Properties<a name="aws-properties-kendra-datasource-confluenceattachmentfieldmappingslist-properties"></a>

`ConfluenceAttachmentFieldMappingsList`  <a name="cfn-kendra-datasource-confluenceattachmentfieldmappingslist-confluenceattachmentfieldmappingslist"></a>
Specifies one or more `ConfluenceAttachmentToIndexFieldMapping` objects\.  
*Required*: No  
*Type*: [List](#aws-properties-kendra-datasource-confluenceattachmentfieldmappingslist) of [ConfluenceAttachmentToIndexFieldMapping](aws-properties-kendra-datasource-confluenceattachmenttoindexfieldmapping.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)