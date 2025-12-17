This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## 🧪 การทดสอบระบบ (Testing)
หากต้องการทดสอบขั้นตอนการชำระเงินบนเว็บไซต์เดโม่ สามารถใช้ข้อมูลสำหรับทดสอบด้านล่างนี้ได้เลยครับ

### สำหรับการชำระเงินผ่าน Stripe (Test Mode)
สามารถใช้ข้อมูลบัตรเครดิตทดสอบของ Stripe ตามด้านล่างนี้:
- **หมายเลขบัตร:** `4242 4242 4242 4242`
- **วันหมดอายุ:** ใส่วันที่ในอนาคต (เช่น 12/25)
- **CVC:** เลข 3 หลัก (เช่น 123)
- **ชื่อบนบัตร:** ใส่ชื่ออะไรก็ได้
- **รหัสไปรษณีย์:** ใส่เลข 5 หลักอะไรก็ได้

### สำหรับการชำระเงินผ่าน PayPal (Sandbox Mode)
จำเป็นต้องใช้บัญชี PayPal Sandbox เพื่อทดสอบการชำระเงิน
- **อีเมล Sandbox:** `sb-swq8q48207763@personal.example.com`
- **รหัสผ่าน:** `rX)fjT]1`

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
