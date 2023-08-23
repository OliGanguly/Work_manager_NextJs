# Project Using Next js - Work Manager
```bash
 npc create-next-app@latest projectName
 run:npm run dev
```
-> page.txt (index.js) make changes 

localhost:3000/profile
- app(root)
  - profile (Folder)
      - page.js
## Technology:
- Next Js [frontend+ backend]
- MongoDb [database]
## Dependency 
- bcryptjs [ convert plain text password to encrypted password ]\

     salt is integer
      we can use hashSync in place of hash then we dont need to use await
     user.password = await bcrypt.hash(user.password,parseInt(process.env.BCRYPT_SALT)); 
- jsonwebtoken [ to generate jwt token ]
  
     

