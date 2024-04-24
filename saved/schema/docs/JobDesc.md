
# Class: JobDesc


Job manifest: job specification attributes which specific job sub-classes inherit

URI: [saved:JobDesc](http://marine.gov.scot/metadata/saved/schema/JobDesc)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[ColumnDesc]<job_scope_modelled%200..*-++[JobDesc&#124;atomic_name:string;title:string%20%3F;job_type:uriorcurie],[ColumnDesc]<job_scope_collected%200..*-++[JobDesc],[ColumnDesc]<job_scope_descriptive%200..*-++[JobDesc],[ManifestDesc]++-%20jobs%201..*>[JobDesc],[ManifestDesc],[ColumnDesc])](https://yuml.me/diagram/nofunky;dir:TB/class/[ColumnDesc]<job_scope_modelled%200..*-++[JobDesc&#124;atomic_name:string;title:string%20%3F;job_type:uriorcurie],[ColumnDesc]<job_scope_collected%200..*-++[JobDesc],[ColumnDesc]<job_scope_descriptive%200..*-++[JobDesc],[ManifestDesc]++-%20jobs%201..*>[JobDesc],[ManifestDesc],[ColumnDesc])

## Referenced by Class

 *  **None** *[jobs](jobs.md)*  <sub>1..\*</sub>  **[JobDesc](JobDesc.md)**

## Attributes


### Own

 * [atomic_name](atomic_name.md)  <sub>1..1</sub>
     * Description: Short-form name / atom: lower-case, no special characters excepting underscores
     * Range: [String](types/String.md)
 * [title](title.md)  <sub>0..1</sub>
     * Description: Concise human-readable name for the element
     * Range: [String](types/String.md)
 * [job_type](job_type.md)  <sub>1..1</sub>
     * Description: While this is analogous to Dublin Core's notion of type, it is specific to jobs proper, because there is a well-defined range of the jobs we know about. Undefined job types cannot be processed.
     * Range: [Uriorcurie](types/Uriorcurie.md)
 * [job_scope_descriptive](job_scope_descriptive.md)  <sub>0..\*</sub>
     * Description: A collection of column descriptions which describe something about the world
     * Range: [ColumnDesc](ColumnDesc.md)
 * [job_scope_collected](job_scope_collected.md)  <sub>0..\*</sub>
     * Description: A collection of column descriptions which are collected or sampled
     * Range: [ColumnDesc](ColumnDesc.md)
 * [job_scope_modelled](job_scope_modelled.md)  <sub>0..\*</sub>
     * Description: A collection of column descriptions which are modelled or simulated
     * Range: [ColumnDesc](ColumnDesc.md)
