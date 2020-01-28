

# CdsDetailSpecifications

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**seniority** | [**SeniorityEnum**](#SeniorityEnum) | The seniority level of the CDS | 
**restructuringType** | [**RestructuringTypeEnum**](#RestructuringTypeEnum) | The restructuring clause | 
**protectStartDay** | **Boolean** | Does the protection leg pay out in the case of default on the start date | 
**payAccruedInterestOnDefault** | **Boolean** | Should accrued interest on the premium leg be paid if a credit event occurs | 
**stubType** | **Integer** | How are coupons handled when the start date is not on a CDS date (i.e. the 20th of March, June, Sept, Dec) | 
**rollFrequency** | [**Tenor**](Tenor.md) |  | 



## Enum: SeniorityEnum

Name | Value
---- | -----
UNKNOWN | &quot;Unknown&quot;
SNR | &quot;SNR&quot;
SUB | &quot;SUB&quot;
JRSUBUT2 | &quot;JRSUBUT2&quot;
PREFT1 | &quot;PREFT1&quot;
SECDOM | &quot;SECDOM&quot;
SNRFOR | &quot;SNRFOR&quot;
SUBLT2 | &quot;SUBLT2&quot;



## Enum: RestructuringTypeEnum

Name | Value
---- | -----
UNKNOWN | &quot;Unknown&quot;
CR | &quot;CR&quot;
MR | &quot;MR&quot;
MM | &quot;MM&quot;
XR | &quot;XR&quot;


