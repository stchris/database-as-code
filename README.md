# The "Database as Code" Manifesto

- Treat your database or other storage system as a code
- All changes and operations with the database and all queries (ideally) against the database should be expressed as a plain old code
- Git (or anything else VCS) is a single source of truth for database code
- SQL actually is a main database language supported by almost all DBMS 
- SQL is not a bytecode for your data and your database, it's a normal human-oriented program language ([why](https://gramin.pro/posts/sql-is-not-a-bytecode-for-data))
- SQL is designed not only for data, but also for metadata
- Database code is not only DDL and other migration scripts, DML and all kinds of SQL scripts too
- Database code is a normal code, and it also needs static analysis, code review (especially by DBA, analysts and business people) , tests and automation of it all
- DBAs and data people should be integrated with Dev and Ops
- Ability to release on demand.

### Resources:
- [Database as Code: a Novel Concept](https://dzone.com/articles/database-as-code-a-novel-concept)
- [Database as Code - the Good, the Bad and the Ugly](https://bytebase.com/blog/database-as-code)
- [The Database Inside Your Codebase](https://feifan.blog/posts/the-database-inside-your-codebase)
- [Database as Code. Not only migrations](https://gramin.pro/posts/database-as-code)

### Talks:
- [Aren't we forgetting someone?](https://speakerdeck.com/tastapod/arent-we-forgetting-someone)

### Tools:
- [Bytebase](https://github.com/bytebase/bytebase) - web-based, zero-config, dependency-free database schema change and version control management tool for developers and DBAs.
- [dbt](https://github.com/dbt-labs/dbt-core) - enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.
- [HugSQL](https://www.hugsql.org) - a Clojure library for embracing SQL, creating a clean separation of Clojure and SQL code.
- [Yesql](https://github.com/krisajenkins/yesql) - a Clojure library for using SQL. Keep the SQL as SQL.
