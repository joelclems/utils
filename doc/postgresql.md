
# SQL

## General

### pb add column not null error:

* [lien Stack OververFlow](https://stackoverflow.com/questions/512451/how-can-i-add-a-column-to-a-postgresql-database-that-doesnt-allow-nulls)

    
```
ALTER TABLE mytable ADD COLUMN mycolumn character varying(50) NOT NULL DEFAULT 'foo';
```