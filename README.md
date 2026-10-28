# Xplicit Air — website rebuild

Six-page responsive rebuild using TypeScript, Vite and Tailwind CSS 4. No PHP runtime is required.

## Run locally

Install Node.js 22.12 or later, then run `npm install` and `npm run dev`. For a production build, run `npm run build` and `npm run preview`.

## Pages

Home `/`, About `/about`, Services `/services`, Projects `/projects`, Resources `/information`, Contact `/contact`. The original PHP URLs are mapped in the client router. Hosts must serve index.html for unmatched page paths (SPA fallback). Configure permanent server redirects from legacy URLs when replacing the production site.

## Features

Responsive navigation, project filtering, service enquiry selection, validated email enquiry preparation, copy-to-clipboard, restrained scroll reveals and an original animated SVG ventilation illustration. Reduced-motion preferences are respected.

## Content and launch notes

Source: https://xplicitair.co.za/index.php and its About.php, Services.php, Portfolio.php, Extra.php and CONTACT.php pages, reviewed 28 October 2026. The site footer dates the original content to 2012. Project involvement is attributed to technicians; historical clients are not presented as current contracts. Published client-reference names and telephone numbers are preserved. The Level 3 BBBEE statement is attributed to the existing website, and the ten-year experience figure is attributed to its company profile. Personnel, accreditation, fleet and contact details need owner verification before launch.

The displayed contact email was xplicitair@gmail.com, while its old mailto target pointed elsewhere. The rebuild consistently uses the displayed address. The enquiry form prepares an email for the visitor to review and send; it does not submit to a backend or claim successful delivery. Connect a verified mail provider if server-based submission is required.

The exact logo image supplied by the user is displayed in the header and footer, unaltered, as public/xplicit-air-logo.png. The team photograph (IMG_0684.JPG) and installation photo (proinst01.jpg) come from the original About.php page. The ventilation illustration is custom SVG, not a photo of company equipment. No external image or font service is required.
