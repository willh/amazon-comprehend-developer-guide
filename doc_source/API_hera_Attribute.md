# Attribute<a name="API_hera_Attribute"></a>

 An extracted segment of the text that is an attribute of an entity, or otherwise related to an entity, such as the dosage of a medication taken\. It contains information about the attribute such as id, begin and end offset within the input text, and the segment of the input text\. 

## Contents<a name="API_hera_Attribute_Contents"></a>

 **BeginOffset**   <a name="comprehend-Type-hera_Attribute-BeginOffset"></a>
 The 0\-based character offset in the input text that shows where the attribute begins\. The offset returns the UTF\-8 code point in the string\.   
Type: Integer  
Required: No

 **EndOffset**   <a name="comprehend-Type-hera_Attribute-EndOffset"></a>
 The 0\-based character offset in the input text that shows where the attribute ends\. The offset returns the UTF\-8 code point in the string\.   
Type: Integer  
Required: No

 **Id**   <a name="comprehend-Type-hera_Attribute-Id"></a>
 The numeric identifier for this attribute\. This is a monotonically increasing id unique within this response rather than a global unique identifier\.   
Type: Integer  
Required: No

 **RelationshipScore**   <a name="comprehend-Type-hera_Attribute-RelationshipScore"></a>
 The level of confidence that Comprehend Medical has that this attribute is correctly related to this entity\.   
Type: Float  
Required: No

 **Score**   <a name="comprehend-Type-hera_Attribute-Score"></a>
 The level of confidence that Comprehend Medical has that the segment of text is correctly recognized as an attribute\.   
Type: Float  
Required: No

 **Text**   <a name="comprehend-Type-hera_Attribute-Text"></a>
 The segment of input text extracted as this attribute\.  
Type: String  
Length Constraints: Minimum length of 1\.  
Required: No

 **Traits**   <a name="comprehend-Type-hera_Attribute-Traits"></a>
 Contextual information for this attribute\.   
Type: Array of [Trait](API_hera_Trait.md) objects  
Required: No

 **Type**   <a name="comprehend-Type-hera_Attribute-Type"></a>
 The type of attribute\.   
Type: String  
Valid Values:` NAME | DOSAGE | ROUTE_OR_MODE | FORM | FREQUENCY | DURATION | GENERIC_NAME | BRAND_NAME | STRENGTH | RATE | ACUITY | TEST_NAME | TEST_VALUE | TEST_UNITS | PROCEDURE_NAME | TREATMENT_NAME | DATE | AGE | CONTACT_POINT | EMAIL | IDENTIFIER | URL | ADDRESS | PROFESSION | SYSTEM_ORGAN_SITE | DIRECTION | QUALITY | QUANTITY`   
Required: No

## See Also<a name="API_hera_Attribute_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:
+  [AWS SDK for C\+\+](https://docs.aws.amazon.com/goto/SdkForCpp/comprehendmedical-2018-10-30/Attribute) 
+  [AWS SDK for Go](https://docs.aws.amazon.com/goto/SdkForGoV1/comprehendmedical-2018-10-30/Attribute) 
+  [AWS SDK for Java](https://docs.aws.amazon.com/goto/SdkForJava/comprehendmedical-2018-10-30/Attribute) 
+  [AWS SDK for Ruby V2](https://docs.aws.amazon.com/goto/SdkForRubyV2/comprehendmedical-2018-10-30/Attribute) 