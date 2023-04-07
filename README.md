# open-schema
Collection of AVRO schemas that are commonly use to design various Information management systems. 

#Insperation
We plan to create open repository of various AVRO schema that can be used commonly without reinventing them. 

# Guidelines
Needs to be valid AVRO
Schema name, namespace and field names must be upper case. 
Additional Information is stored in JSON format inside Doc
Fields can be of only premitive and logical data types and array to allow null values. Do not use complex types such as "record", "maps" etc. They can have their saperate shcema. 
Idea is to create relational model of AVRO schemas. Relationships can be defined with "Ref" tag as part of "Doc". 
Field Doc can contain
  * Desc (string)
  * PrimaryKey (bool)
  * Ref (string)
  * GroupName (string)
  * GroupOrder (int)
  * OrderInsideGroup (int)
  


