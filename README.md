# team-demo-next-s3-firebase-spaces-stripe

# 🚀 🚀

https://github.com/coding-to-music/team-demo-next-s3-firebase-spaces-stripe

From / By https://github.com/LEDUCLINH/teamDemo

## Environment variables:

```java
CONTACT_EMAIL_TO=info@yourdomain.com
EMAIL_FROM=info@yourdomain.com

EVENT_WEBHOOK_SECRET=myeventwebhooksecret

FIREBASE_PROJECT_ID=XXXXXX
FIREBASE_PRIVATE_KEY=
FIREBASE_CLIENT_EMAIL_NAME=firebase-adminsdk-XXXXX

HASURA_ADMIN_SECRET=myadminsecretkey

MAILGUN_API_KEY=
MAILGUN_DOMAIN=mg.yourdomain.com

NEXT_PUBLIC_BASE_URL=http://localhost:3000
NEXT_PUBLIC_HASURA_ENDPOINT=http://localhost:8080/v1/graphql
NEXT_PUBLIC_HASURA_WEBSOCKET_ENDPOINT=ws://localhost:8080/v1/graphql
NEXT_PUBLIC_RECAPTCHA_SITE_KEY=
NEXT_PUBLIC_STRAPI_ENDPOINT=https:/localhost:1337/graphql

SPACES_ENDPOINT=
SPACES_KEY=
SPACES_SECRET=
SPACES_BUCKET=uploads.1stkare
SPACES_CDN_BASE_URL=https://uploads.1stkare.com

STRIPE_PRODUCT_DONATION=
STRIPE_PRODUCT_POST_SPONSORSHIP_INDIVIDUAL=
STRIPE_PRODUCT_POST_SPONSORSHIP_BUSINESS=
STRIPE_PRODUCT_POST_SUBSCRIPTION_INDIVIDUAL=
STRIPE_PRODUCT_POST_SUBSCRIPTION_BUSINESS=
STRIPE_PRODUCT_USER_SUBSCRIPTION=
STRIPE_SECRET_KEY=sk_test_
STRIPE_WEBHOOK_SECRET=whsec_

VERCEL_TOKEN=
VERCEL_ORG_ID=
VERCEL_PROJECT_ID=
```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/team-demo-next-s3-firebase-spaces-stripe.git
git push -u origin main
```

# 1stKare

1stKare - Web

## Setup

1. Copy `.env.example` to a new `.env.local` file, and configure it as needed

2. `pnpm install`

## Scripts

```bash
// development:
pnpm dev

// production:
pnpm build
pnpm start
```
