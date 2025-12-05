# مرحبًا بك في Remix + Cloudflare Workers!

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/cloudflare/templates/tree/main/remix-starter-template)

بناء تطبيق كامل (Fullstack) باستخدام Remix ونشره على Cloudflare Workers.

- 📖 [وثائق Remix](https://remix.run/docs)
- 📖 [دليل Remix على Cloudflare](https://remix.run/guides/vite#cloudflare)

## التطوير

تشغيل خادم التطوير:

```sh
npm run dev
```

لتشغيل Wrangler (للبناء والنشر):

```sh
npm run build
npm start
```

## إنشاء الأنواع (Typegen)

توليد أنواع TypeScript لربط Cloudflare في `wrangler.toml`:

```sh
npm run typegen
```

ستحتاج إلى إعادة تشغيل `typegen` كلما قمت بتغيير `wrangler.toml`.

## النشر

إذا لم تكن تملك حسابًا، فأنشئ حساب Cloudflare من هنا: [إنشاء حساب Cloudflare](https://dash.cloudflare.com/sign-up). بعد التحقق من بريدك، اذهب إلى لوحة التحكم وأنشئ نطاق Cloudflare Workers الفرعي المجاني الخاص بك.

بعد ذلك يمكنك بناء التطبيق:

```sh
npm run build
```

ثم نشره:

```sh
npm run deploy
```

## التنسيق (Styling)

هذا القالب يأتي مُجهَّزًا مسبقًا بواجهة Tailwind CSS لتجربة بداية بسيطة. يمكنك استخدام أي إطار عمل CSS تفضله. راجع توثيق Vite الخاص بـ CSS للمزيد من المعلومات: https://vitejs.dev/guide/features.html#css
# Welcome to Remix + Cloudflare Workers!

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/cloudflare/templates/tree/main/remix-starter-template)

<!-- dash-content-start -->

Build a fullstack Remix application, deployed to Cloudflare Workers.

- 📖 [Remix docs](https://remix.run/docs)
- 📖 [Remix Cloudflare docs](https://remix.run/guides/vite#cloudflare)

<!-- dash-content-end -->

## Development

Run the dev server:

```sh
npm run dev
```

To run Wrangler:

```sh
npm run build
npm start
```

## Typegen

Generate types for your Cloudflare bindings in `wrangler.toml`:

```sh
npm run typegen
```

You will need to rerun typegen whenever you make changes to `wrangler.toml`.

## Deployment

If you don't already have an account, then [create a cloudflare account here](https://dash.cloudflare.com/sign-up) and after verifying your email address with Cloudflare, go to your dashboard and set up your free custom Cloudflare Workers subdomain.

Once that's done, you should be able to build your app:

```sh
npm run build
```

And deploy it:

```sh
npm run deploy
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever css framework you prefer. See the [Vite docs on css](https://vitejs.dev/guide/features.html#css) for more information.

#### تعريب: حسن الدوي

---
MADE WITH ❤️ IN BAHRAIN 🇧🇭 BY [HASAN ALDOY](https://github.com/aldoyh)