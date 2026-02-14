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

## 7. Fetching Data

Fetching revenue data from database<br>
![Fetching revenue data](screenshots/fetching-revenue-console.png)<br>
![Fetching revenue data](screenshots/fetching-revenue-browser.png)

Getting latest invoices from database<br>
![Getting latest invoices](screenshots/getting-latest-invoices.png)

Getting card data from database<br>
![Getting card data](screenshots/getting-card-data.png)

## 8. Static and Dynamic Rendering

Fetching revenue with delay<br>
![Fetching revenue with delay](screenshots/fetch-revenue-with-delay.png)

## 9. Streaming

Dashboard page skeleton<br>
![Dashboard page skeleton](screenshots/dashboard-page-skeleton.png)

Created [overview](<app/dashboard/(overview)/>) directory with [page.tsx](<app/dashboard/(overview)/page.tsx>) and [loading.tsx](<app/dashboard/(overview)/loading.tsx>)<br>
![Overview directory](screenshots/overview-directory.png)

Loading `<RevenueChart />` with `<Suspense />` <br>
![Loading RevenueChart](screenshots/loading-revenue-separately.png)

Implementing `<Suspense />` for `<CardWrapper />` in [page.tsx](<app/dashboard/(overview)/page.tsx>)<br>
![Implementing Suspense for CardWrapper](screenshots/cardWrapper-page.png)

Implementing `<Card />` components in [cards.tsx](app/ui/dashboard/cards.tsx)<br>
![Implementing Card components](screenshots/cards-realisation-page.png)

## 10. Adding Search and Pagination

Search implementation in [search.tsx](app/ui/search.tsx)<br>
![Search implementation](screenshots/search-with-debounce-console.png)<br>
![Search implementation](screenshots/search-with-debounce-browser.png)

Added pagination to [invoices page](app/dashboard/invoices/page.tsx)<br>
![Pagination](screenshots/pagination.png)

## 11. Mutating Data

Added [invoice creation page](app/dashboard/invoices/create/page.tsx)<br>
![Create invoice page](screenshots/create-invoice-page.png)

Checking console for raw data from form<br>
![Checking console for raw data from form](screenshots/checking-console-for-raw-data-from-form.png)

Updated [actions.ts](app/lib/actions.ts) with database query<br>
Create new invoice for checking<br>
![Create new invoice for checking](screenshots/new-invoice-checking.png)

Created [edit invoice page](app/dashboard/invoices/[id]/edit/page.tsx)<br>
![Edit invoice page](screenshots/edit-invoice-page.png)

Updated [actions.ts](app/lib/actions.ts), [edit-form.tsx](app/ui/invoices/edit-form.tsx), [button.tsx](app/ui/button.tsx) and checking update functionality<br>
![Update existing invoice for checking](screenshots/update-existing-invoice-for-checking.png)

Updated [buttons.tsx](app/ui/invoices/buttons.tsx), [actions.ts](app/lib/actions.ts) and checking delete functionality<br>
![Delete invoice for checking](screenshots/delete-invoice-for-checking.png)

## 12. Handling Errors

Added error handling with `try-catch` blocks to [actions.ts](app/lib/actions.ts)<br>
Testing error handling with temporary `throw new Error()` function <br>
![Error handling](screenshots/error-handling-console.png)<br>
![Error handling](screenshots/error-handling-browser.png)

Created [error.tsx](app/dashboard/invoices/error.tsx) file to handle errors in [invoices page](app/dashboard/invoices/page.tsx)<br>
![Error handling](screenshots/component-error-handling-browser.png)

Created [not-found.tsx](app/dashboard/invoices/[id]/edit/not-found.tsx) file to handle not-found errors in [edit invoice page](app/dashboard/invoices/[id]/edit/page.tsx)<br>
![Not-found handling](screenshots/not-found-handling-browser.png)

## 13. Improving Accessibility
