## 1. Getting Started

Console:<br>
![Console](screenshots/startup-dev-server-console.jpg)

Browser:<br>
![Browser](screenshots/startup-dev-server-browser.jpg)

## 2. CSS-стилізація

Added code to [layout.tsx](app/layout.tsx)<br>
![Layout.tsx](screenshots/styles-layout-browser.jpg)

Added black triangle to [main page](app/page.tsx) with tailwind<br>
![Black triangle](screenshots/styles-black-triangle.png)

Added styles to [home.module.css](app/ui/home.module.css)<br>
![Home.module.css](screenshots/styles-home-module-css.png)

## 3. Optimizing Fonts and Images

Created [fonts.ts](app/ui/fonts.ts), added Inter font to [layout.tsx](app/layout.tsx)<br>
![Fonts](screenshots/fonts-inter.png)

Added Lusitana font to [fonts.ts](app/ui/fonts.ts) and implemented it in [main page](app/page.tsx)<br>
![Fonts](screenshots/fonts-lusitana.png)

Added hero image to [main page](app/page.tsx)<br>
![Hero image](screenshots/hero-image-desktop.png)

Added mobile hero image to [main page](app/page.tsx)<br>
![Hero image](screenshots/hero-image-mobile.png)

## 4. Creating Layouts and Pages

Created [dashboard page](app/dashboard/page.tsx)<br>
![Dashboard page](screenshots/dashboard-page.png)

Created [customers](app/dashboard/customers/page.tsx) & [invoices](app/dashboard/invoices/page.tsx) pages<br>
![Customers page](screenshots/customers-page.png)<br>
![Invoices page](screenshots/invoices-page.png)

Created [dashboard layout](app/dashboard/layout.tsx)<br>
![Dashboard layout](screenshots/dashboard-layout.png)

## 5. Navigating Between Pages

Replaced `<a>` with `<Link>` in [nav-links.tsx](app/ui/dashboard/nav-links.tsx)<br>
Added `usePathname` and `clsx` to [nav-links.tsx](app/ui/dashboard/nav-links.tsx)<br>
![Nav-links.tsx](screenshots/nav-links.png)

## 6. Setting Up Your Database

Deployed project on [Vercel](https://nextjs-tutorial-mg1i59xzm-redfields-projects.vercel.app/)<br>
![Vercel](screenshots/vercel-deployment-details.png)<br>
![Vercel](screenshots/vercel-deployment-browser.png)

Created database and implemented into project<br>
![Database](screenshots/database-created.png)<br>
![Database](screenshots/database-implemented.png)

Uncomment code in [route.ts](app/query/route.ts) to test database query<br>
![Database query](screenshots/database-query.png)
