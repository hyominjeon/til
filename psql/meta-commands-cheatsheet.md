# PostgresSQL Meta Commands Cheat Sheet

Meta Command | Definition
-------------|-----------
\d | Show a list of all visible tables, views, sequences, and foreign tables
\d[S][+] _pattern_ | Show all columns, types, tablespace, and any special attributes. + for more information.
\d{E\|i\|s\|t\|v}[S+] [pattern] | List foreign table, index, sequence, table, view respectively. S for system object.
\da[S] [pattern] | List aggregate functions
\db[+] [pattern] | List tablespaces
\dc | List conversions between character-set encodings
\dC | List type casts
\dd | Show the description of objects of type constraint, operator class, operator family, rule, and trigger
\ddp | List default access privilege settings
\dD[S+] | List domains
\des[+] | List foreign servers
\det[+] | List foreign tables
\deu[+] | List user mappings
\dew[+] | List foreign-data wrappers
\df[antwS+] | List functions
\dF[+] | List text search configurations
\dFd[+] | List text search dictionaries
\dFp[+] [ pattern ] | Lists text search parsers.
\dFt[+] [ pattern ] | Lists text search templates. 
\d{g\|u\|x}[+] [ pattern ] | Lists database roles/database roles/installed extensions.
\dl | This is an alias for \lo_list, which shows a list of large objects.
\dL[S+] [ pattern ] | Lists procedural languages. 
\dn[S+] [ pattern ] | Lists schemas (namespaces).
\do[S] [ pattern ] | Lists operators with their operand and return types. 
\dO[S+] [ pattern ] | Lists collations.
\dp [ pattern ] | Lists tables, views and sequences with their associated access privileges. 
\drds [ role-pattern [ database-pattern ] ] | Lists defined configuration settings. 
\dT[S+] [ pattern ] | Lists data types. 
