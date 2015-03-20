# IDLYAMI IDL to C++ mapping #

| **IDL Type** | **C++ Type** | **in C++ Type** | **out C++ Type** | **inout C++ Type** |
|:-------------|:-------------|:----------------|:-----------------|:-------------------|
| primitive | primitive | primitive | primitive& | primitive& |
| string | std::string | const std::string& | std::string& | std::string& |
| any | idlyami::any | const idlyami::any& | idlyami::any& | idlyami::any& |
| struct S | S | const S& | S& | S& |
| sequence< T > | std::vector< T > | const std::vector< T >& | std::vector< T >& | std::vector< T >& |