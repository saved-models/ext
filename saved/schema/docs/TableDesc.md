
# Class: TableDesc


Manifest: data source descriptive attributes

URI: [saved:TableDesc](https://marine.gov.scot/metadata/saved/schema/TableDesc)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[ScopeDesc]-%20table%201..1>[TableDesc&#124;atomic_name:string;title:string%20%3F;description:string%20%3F;resource_path:uri;resource_hash:string;schema_path_yaml:uri;schema_path_ttl:uri%20%3F],[ManifestDesc]++-%20tables%201..*>[TableDesc],[ScopeDesc],[ManifestDesc])](https://yuml.me/diagram/nofunky;dir:TB/class/[ScopeDesc]-%20table%201..1>[TableDesc&#124;atomic_name:string;title:string%20%3F;description:string%20%3F;resource_path:uri;resource_hash:string;schema_path_yaml:uri;schema_path_ttl:uri%20%3F],[ManifestDesc]++-%20tables%201..*>[TableDesc],[ScopeDesc],[ManifestDesc])

## Referenced by Class

 *  **None** *[table](table.md)*  <sub>1..1</sub>  **[TableDesc](TableDesc.md)**
 *  **None** *[tables](tables.md)*  <sub>1..\*</sub>  **[TableDesc](TableDesc.md)**

## Attributes


### Own

 * [atomic_name](atomic_name.md)  <sub>1..1</sub>
     * Description: Short-form name / atom: lower-case, no special characters excepting underscores
     * Range: [String](types/String.md)
 * [title](title.md)  <sub>0..1</sub>
     * Description: Concise human-readable name for the element
     * Range: [String](types/String.md)
 * [description](description.md)  <sub>0..1</sub>
     * Description: Human-readable description of the element
     * Range: [String](types/String.md)
 * [resource_path](resource_path.md)  <sub>1..1</sub>
     * Description: Path or URI of resource
     * Range: [Uri](types/Uri.md)
 * [resource_hash](resource_hash.md)  <sub>1..1</sub>
     * Description: Checksum of resource
     * Range: [String](types/String.md)
 * [schema_path_yaml](schema_path_yaml.md)  <sub>1..1</sub>
     * Description: Path or URI of schema associated with resource (LinkML YAML)
     * Range: [Uri](types/Uri.md)
 * [schema_path_ttl](schema_path_ttl.md)  <sub>0..1</sub>
     * Description: Path of URI of schema associated with resource (RDF/TTL conversion of LinkML YAML)
     * Range: [Uri](types/Uri.md)
