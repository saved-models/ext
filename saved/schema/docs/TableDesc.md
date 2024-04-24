
# Class: TableDesc


Job manifest: data source descriptive attributes

URI: [saved:TableDesc](http://marine.gov.scot/metadata/saved/schema/TableDesc)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[ManifestDesc]++-%20tables%201..*>[TableDesc&#124;atomic_name:string;title:string%20%3F;description:string%20%3F;resource_path:uriorcurie;schema_path:uriorcurie;resource_hash:string],[ManifestDesc])](https://yuml.me/diagram/nofunky;dir:TB/class/[ManifestDesc]++-%20tables%201..*>[TableDesc&#124;atomic_name:string;title:string%20%3F;description:string%20%3F;resource_path:uriorcurie;schema_path:uriorcurie;resource_hash:string],[ManifestDesc])

## Referenced by Class

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
     * Range: [Uriorcurie](types/Uriorcurie.md)
 * [schema_path](schema_path.md)  <sub>1..1</sub>
     * Description: Path or URI of schema associated with resource
     * Range: [Uriorcurie](types/Uriorcurie.md)
 * [resource_hash](resource_hash.md)  <sub>1..1</sub>
     * Description: Checksum of resource
     * Range: [String](types/String.md)
