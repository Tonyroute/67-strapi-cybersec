# 🚀 Cybersec KMUTNB
### Docker and Security ??? 

### Week of Compose
<sub>🤫 Let's start
```
ให้ดำเนินสร้าง branch ใหม่ที่ชื่อว่า create-docker-image จาก develop เพื่อเก็บเป็นข้อมูล history หลังจากนั้นให้กลับไปยัง branch  develop เพื่อสร้างไฟล์ docker-compose.yml เพื่อทดสอบใช้งาน docker image ที่เราพึ่งสร้างพร้อมทั้งให้กำหนดมีทั้ง  strapi และ database 

ตัวอย่างชื่อไฟล์ docker-compose.yml


version: '3'
services:
    app:
        ....
    db:
        ....

***ในตัว configure ของ docker-compose.yml ไม่ควรมีข้อมูลที่เป็นข้อมูลสำคัญของระบบ และที่สำคัญระบบยังคงทำงานได้ปกติ***
```






Strapi [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI)

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project including [Strapi Cloud](https://cloud.strapi.io). Browse the [deployment section of the documentation](https://docs.strapi.io/dev-docs/deployment) to find the best solution for your use case.

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

