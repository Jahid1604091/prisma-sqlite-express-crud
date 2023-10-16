# Prisma (sql/NoSql)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ac703bab-e1b4-4984-85ae-3f2769efc34d/6454186b-1c0e-46cf-929e-3e09e0740528/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ac703bab-e1b4-4984-85ae-3f2769efc34d/f46664d2-b03c-4308-a093-4e4f5c12dd3e/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ac703bab-e1b4-4984-85ae-3f2769efc34d/1cdb56b8-c3f8-47ba-918a-6141e558e47a/Untitled.png)

**npm i prisma** → to install prisma

**npm i @prisma/client** → query builder

**npx prisma init** → will add prisma related basic files like scema env etc.

**npx prisma studio** -.> to start studio

**npx prisma migrate dev** → to create table

**npx prisma generate** → if changes any attribute/field and also run migrate **with default value**
Default  DATABASE_URL="postgresql://johndoe:randompassword@localhost:5432/mydb?schema=public”

**For Sqlite**:: change in env and schema → sqlite