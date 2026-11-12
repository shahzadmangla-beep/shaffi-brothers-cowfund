# Shaffi Brothers CowFund

Mobile-first private family cattle investment web app using Supabase for authentication and row-level-secured data. Website code is public; financial records remain private in Supabase.

## Publish on GitHub Pages

Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save. Your site will appear at the Pages URL shown in settings.

## Supabase sign-in

In Supabase Authentication → URL Configuration, add the final GitHub Pages URL (including trailing slash) to **Redirect URLs**. Keep Supabase's service-role and secret keys out of public files. Only the publishable key is used by this static app.

## Bookkeeping

Four brothers contribute PKR 20,000 per month each. Cattle assets use original purchase cost. The caretaker receives 50% of positive realized profit, and remaining family profit is reinvested. Historical cattle sale proceeds were already reinvested and are not counted twice. Opening active cattle cost PKR 762,000, provisional cash PKR 0. The historical PKR 85,000 family profit is for performance reporting, not extra cash.

## Accounts

Admin account is registered in Supabase. The other three brothers need their email addresses added in the app by the admin before accessing records. Only authorized authenticated accounts can read the data. All edits rely on Supabase RLS.

## Install

Open the GitHub Pages URL on Android Chrome or iPhone Safari, then choose Add to Home screen. You can also bookmark it on a desktop.
