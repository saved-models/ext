
# Class: ScopeDesc


Manifest: column scope description and attributes including variable underpinning the column

URI: [saved:ScopeDesc](https://marine.gov.scot/metadata/saved/schema/ScopeDesc)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[TableDesc],[TableDesc]<table%201..1-%20[ScopeDesc&#124;column:string],[ExtColumnDesc]<variable%201..1-%20[ScopeDesc],[JobDesc]++-%20job_scope_collected%200..*>[ScopeDesc],[JobDesc]++-%20job_scope_descriptive%200..*>[ScopeDesc],[JobDesc]++-%20job_scope_modelled%200..*>[ScopeDesc],[JobDesc],[ExtColumnDesc])](https://yuml.me/diagram/nofunky;dir:TB/class/[TableDesc],[TableDesc]<table%201..1-%20[ScopeDesc&#124;column:string],[ExtColumnDesc]<variable%201..1-%20[ScopeDesc],[JobDesc]++-%20job_scope_collected%200..*>[ScopeDesc],[JobDesc]++-%20job_scope_descriptive%200..*>[ScopeDesc],[JobDesc]++-%20job_scope_modelled%200..*>[ScopeDesc],[JobDesc],[ExtColumnDesc])

## Referenced by Class

 *  **None** *[job_scope](job_scope.md)*  <sub>0..\*</sub>  **[ScopeDesc](ScopeDesc.md)**
 *  **None** *[job_scope_collected](job_scope_collected.md)*  <sub>0..\*</sub>  **[ScopeDesc](ScopeDesc.md)**
 *  **None** *[job_scope_descriptive](job_scope_descriptive.md)*  <sub>0..\*</sub>  **[ScopeDesc](ScopeDesc.md)**
 *  **None** *[job_scope_modelled](job_scope_modelled.md)*  <sub>0..\*</sub>  **[ScopeDesc](ScopeDesc.md)**

## Attributes


### Own

 * [column](column.md)  <sub>1..1</sub>
     * Description: Column name in table
     * Range: [String](types/String.md)
 * [variable](variable.md)  <sub>1..1</sub>
     * Description: Name of variable underpinning column, specific to the job, used for pattern-matching
     * Range: [ExtColumnDesc](ExtColumnDesc.md)
 * [table](table.md)  <sub>1..1</sub>
     * Description: Table description from which column is drawn, specifically matching the `atomic_name' field of a given instance of a `TableDesc' class.
     * Range: [TableDesc](TableDesc.md)
