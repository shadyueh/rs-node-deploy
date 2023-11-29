

npm init -y
npm install -D typescript @types/node tsx tsup 
npx tsc --init
npm i fastify
npm i prisma -D
npm i @prisma/client
npx prisma init

npx prisma migrate dev
npm i zod
npm run dev
npx prisma studio
sudo apt install httpie
http localhost:3333/users