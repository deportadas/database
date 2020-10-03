# database
comandos sql probados 

en sqlite3
table gastos
CREATE TABLE "gastos" (
	"_id"	TEXT,
	"id"	TEXT,
	"gasto"	NUMERIC,
	"status"	TEXT,
	"fecha"	TEXT
)

SELECT SUM(gasto) FROM gastos;
