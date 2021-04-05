テキストファイルからMySQLにデータを挿入

・CreatAllTable.h  
include each lower function.  

CheckTotalTable(Statement* stmt)  
InsertType1Data(Connection* con, Statement* stmt, char *fname1)  
InsertPokemonData(Connection* con, Statement* stmt, char* fname3)  
InsertType2Data(Connection* con, Statement* stmt, char *fname1)  
CheckType1Data(Statement* stmt)  
CheckType2Data(Statement* stmt)  
CheckPokemonData(Statement* stmt)   
CheckColourData(Statement* stmt)  
InsertColourData(Connection* con, Statement* stmt, char *fname2)  
DeleteAllTableOrView(Statement* stmt, string DATABASE)  
