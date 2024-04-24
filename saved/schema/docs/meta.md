
# meta


**metamodel version:** 1.7.0

**version:** None





### Classes

 * [ColumnDesc](ColumnDesc.md) - Job manifest: column scope description and annotations
 * [JobDesc](JobDesc.md) - Job manifest: job specification attributes which specific job sub-classes inherit
 * [ManifestDesc](ManifestDesc.md) - Job manifest: complete specification
 * [TableDesc](TableDesc.md) - Job manifest: data source descriptive attributes

### Mixins


### Slots

 * [atomic_name](atomic_name.md) - Short-form name / atom: lower-case, no special characters excepting underscores
 * [column](column.md) - Column name in table
 * [column_collected](column_collected.md) - Column describes collected data
     * [count_fish_collected](count_fish_collected.md) - Sampled number of fish in the farm
     * [fish_length](fish_length.md) - Length of fish expressed (mm)
     * [fish_mass](fish_mass.md) - Weight of fish expressed (g)
     * [fish_species_common](fish_species_common.md) - Common name of species sampled
     * [fish_species_scientific](fish_species_scientific.md) - Scientific name of species sampled
     * [lice_af_average](lice_af_average.md) - Average number of Salmon lice (adult female) per fish
     * [lice_af_total](lice_af_total.md) - Total number of Salmon lice per fish
     * [lice_density_collected](lice_density_collected.md) - Sampled lice density (lice per m³)
 * [column_descriptive](column_descriptive.md) - Column describes data about the world
     * [cage_id](cage_id.md) - Semi-numeric cage identifier, related to station/site
     * [depth](depth.md) - Depth in metres
     * [easting](easting.md) - 'Y'-positional data relative to point of origin
     * [global_coordinate_system](global_coordinate_system.md) - Global coordinate system (GCS) reference point of origin
     * [latitude](latitude.md) - Latitude
     * [longitude](longitude.md) - Longitude
     * [national_grid_reference](national_grid_reference.md) - National grid reference (NGR) point of origin
     * [northing](northing.md) - 'X'-positional data relative to point of origin
     * [notes](notes.md) - Notes pertinent to observation, a set of observations, or a data-set
     * [series](series.md) - Data series to which a given observation belongs
     * [site_id](site_id.md) - Fish farm station/site global ID
     * [site_name](site_name.md) - Fish farm station/site local name
 * [column_modelled](column_modelled.md) - Column describes modelled data
     * [count_fish_interpolated](count_fish_interpolated.md) - Interpolated number of fish in the farm
     * [lice_density_modelled](lice_density_modelled.md) - Modelled lice density (lice per m³)
 * [description](description.md) - Human-readable description of the element
 * [gcp_source](gcp_source.md) - GCP account of the generator of the manifest
 * [hash](hash.md) - Checksum of some file
     * [resource_hash](resource_hash.md) - Checksum of resource
 * [job_scope](job_scope.md) - A collection of column descriptions
     * [job_scope_collected](job_scope_collected.md) - A collection of column descriptions which are collected or sampled
     * [job_scope_descriptive](job_scope_descriptive.md) - A collection of column descriptions which describe something about the world
     * [job_scope_modelled](job_scope_modelled.md) - A collection of column descriptions which are modelled or simulated
 * [job_type](job_type.md) - While this is analogous to Dublin Core's notion of type, it is specific to jobs proper, because there is a well-defined range of the jobs we know about. Undefined job types cannot be processed.
 * [jobs](jobs.md) - Specification of operations to run on resources and schemas provided
 * [local_version](local_version.md) - Version number of local submission utility
 * [path](path.md) - Path or URI
     * [resource_path](resource_path.md) - Path or URI of resource
     * [schema_path](schema_path.md) - Path or URI of schema associated with resource
 * [provenance](provenance.md) - Provenance of an element, or a set of elements. This is distinct from Dublin Core's notion of provenance, which concerns any changes in ownership/custody of the resource since its creation.
 * [table](table.md) - Table description from which column is drawn, specifically matching the `atomic_name' field of a given instance of a `TableDesc' class.
 * [tables](tables.md) - Specification of mappings between resources and schemas, as well as columns or dimensions to bring into into scope
 * [title](title.md) - Concise human-readable name for the element
 * [type](type.md) - Nature or genre of the element
 * [variable](variable.md) - Name of variable underpinning column, specific to the job

### Enums


### Subsets


### Types


#### Built in

 * **Bool**
 * **Curie**
 * **Decimal**
 * **ElementIdentifier**
 * **NCName**
 * **NodeIdentifier**
 * **URI**
 * **URIorCURIE**
 * **XSDDate**
 * **XSDDateTime**
 * **XSDTime**
 * **float**
 * **int**
 * **str**

#### Defined

 * [LatLonType](types/LatLonType.md)  (**str**) 
 * [Boolean](types/Boolean.md)  (**Bool**)  - A binary (true or false) value
 * [Curie](types/Curie.md)  (**Curie**)  - a compact URI
 * [Date](types/Date.md)  (**XSDDate**)  - a date (year, month and day) in an idealized calendar
 * [DateOrDatetime](types/DateOrDatetime.md)  (**str**)  - Either a date or a datetime
 * [Datetime](types/Datetime.md)  (**XSDDateTime**)  - The combination of a date and time
 * [Decimal](types/Decimal.md)  (**Decimal**)  - A real number with arbitrary precision that conforms to the xsd:decimal specification
 * [Double](types/Double.md)  (**float**)  - A real number that conforms to the xsd:double specification
 * [Float](types/Float.md)  (**float**)  - A real number that conforms to the xsd:float specification
 * [Integer](types/Integer.md)  (**int**)  - An integer
 * [Jsonpath](types/Jsonpath.md)  (**str**)  - A string encoding a JSON Path. The value of the string MUST conform to JSON Point syntax and SHOULD dereference to zero or more valid objects within the current instance document when encoded in tree form.
 * [Jsonpointer](types/Jsonpointer.md)  (**str**)  - A string encoding a JSON Pointer. The value of the string MUST conform to JSON Point syntax and SHOULD dereference to a valid object within the current instance document when encoded in tree form.
 * [Ncname](types/Ncname.md)  (**NCName**)  - Prefix part of CURIE
 * [Nodeidentifier](types/Nodeidentifier.md)  (**NodeIdentifier**)  - A URI, CURIE or BNODE that represents a node in a model.
 * [Objectidentifier](types/Objectidentifier.md)  (**ElementIdentifier**)  - A URI or CURIE that represents an object in the model.
 * [Sparqlpath](types/Sparqlpath.md)  (**str**)  - A string encoding a SPARQL Property Path. The value of the string MUST conform to SPARQL syntax and SHOULD dereference to zero or more valid objects within the current instance document when encoded as RDF.
 * [String](types/String.md)  (**str**)  - A character string
 * [Time](types/Time.md)  (**XSDTime**)  - A time object represents a (local) time of day, independent of any particular day
 * [Uri](types/Uri.md)  (**URI**)  - a complete URI
 * [Uriorcurie](types/Uriorcurie.md)  (**URIorCURIE**)  - a URI or a CURIE
