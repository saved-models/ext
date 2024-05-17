
# Class: ManifestDesc


Manifest: job invocation specification

URI: [saved:ManifestDesc](https://marine.gov.scot/metadata/saved/schema/ManifestDesc)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[TableDesc],[JobDesc]<jobs%201..*-++[ManifestDesc&#124;atomic_name:string;gcp_source:string%20%3F;local_version:string%20%3F],[TableDesc]<tables%201..*-++[ManifestDesc],[JobDesc])](https://yuml.me/diagram/nofunky;dir:TB/class/[TableDesc],[JobDesc]<jobs%201..*-++[ManifestDesc&#124;atomic_name:string;gcp_source:string%20%3F;local_version:string%20%3F],[TableDesc]<tables%201..*-++[ManifestDesc],[JobDesc])

## Attributes


### Own

 * [atomic_name](atomic_name.md)  <sub>1..1</sub>
     * Description: Short-form name / atom: lower-case, no special characters excepting underscores
     * Range: [String](types/String.md)
 * [tables](tables.md)  <sub>1..\*</sub>
     * Description: Specification of mappings between resources and schemas, as well as columns or dimensions to bring into into scope
     * Range: [TableDesc](TableDesc.md)
 * [jobs](jobs.md)  <sub>1..\*</sub>
     * Description: Specification of operations to run on resources and schemas provided
     * Range: [JobDesc](JobDesc.md)
 * [gcp_source](gcp_source.md)  <sub>0..1</sub>
     * Description: GCP account of the generator of the manifest
     * Range: [String](types/String.md)
 * [local_version](local_version.md)  <sub>0..1</sub>
     * Description: Version number of local submission utility
     * Range: [String](types/String.md)
