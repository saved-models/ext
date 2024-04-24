
# Class: ColumnDesc


Job manifest: column scope description and annotations
This has three elements:
  1. The column name
  2. The table from which the column is or columns are drawn
  3. The variable underpinning the column, which is specific to the job.

URI: [saved:ColumnDesc](http://marine.gov.scot/metadata/saved/schema/ColumnDesc)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[JobDesc]++-%20job_scope_collected%200..*>[ColumnDesc&#124;column:string;variable:uriorcurie;table:uriorcurie],[JobDesc]++-%20job_scope_descriptive%200..*>[ColumnDesc],[JobDesc]++-%20job_scope_modelled%200..*>[ColumnDesc],[JobDesc])](https://yuml.me/diagram/nofunky;dir:TB/class/[JobDesc]++-%20job_scope_collected%200..*>[ColumnDesc&#124;column:string;variable:uriorcurie;table:uriorcurie],[JobDesc]++-%20job_scope_descriptive%200..*>[ColumnDesc],[JobDesc]++-%20job_scope_modelled%200..*>[ColumnDesc],[JobDesc])

## Referenced by Class

 *  **None** *[job_scope](job_scope.md)*  <sub>0..\*</sub>  **[ColumnDesc](ColumnDesc.md)**
 *  **None** *[job_scope_collected](job_scope_collected.md)*  <sub>0..\*</sub>  **[ColumnDesc](ColumnDesc.md)**
 *  **None** *[job_scope_descriptive](job_scope_descriptive.md)*  <sub>0..\*</sub>  **[ColumnDesc](ColumnDesc.md)**
 *  **None** *[job_scope_modelled](job_scope_modelled.md)*  <sub>0..\*</sub>  **[ColumnDesc](ColumnDesc.md)**

## Attributes


### Own

 * [column](column.md)  <sub>1..1</sub>
     * Description: Column name in table
     * Range: [String](types/String.md)
 * [variable](variable.md)  <sub>1..1</sub>
     * Description: Name of variable underpinning column, specific to the job
     * Range: [Uriorcurie](types/Uriorcurie.md)
 * [table](table.md)  <sub>1..1</sub>
     * Description: Table description from which column is drawn, specifically matching the `atomic_name' field of a given instance of a `TableDesc' class.
     * Range: [Uriorcurie](types/Uriorcurie.md)
