---
title: "Third post"
description: "Lorem ipsum dolor sit amet"
pubDate: "Jul 22 2022"
heroImage: "/blog-placeholder-2.jpg"
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vitae ultricies leo integer malesuada nunc vel risus commodo viverra. Adipiscing enim eu turpis egestas pretium. Euismod elementum nisi quis eleifend quam adipiscing. In hac habitasse platea dictumst vestibulum. Sagittis purus sit amet volutpat. Netus et malesuada fames ac turpis egestas. Eget magna fermentum iaculis eu non diam phasellus vestibulum lorem. Varius sit amet mattis vulputate enim. Habitasse platea dictumst quisque sagittis. Integer quis auctor elit sed vulputate mi. Dictumst quisque sagittis purus sit amet.

Morbi tristique senectus et netus. Id semper risus in hendrerit gravida rutrum quisque non tellus. Habitasse platea dictumst quisque sagittis purus sit amet. Tellus molestie nunc non blandit massa. Cursus vitae congue mauris rhoncus. Accumsan tortor posuere ac ut. Fringilla urna porttitor rhoncus dolor. Elit ullamcorper dignissim cras tincidunt lobortis. In cursus turpis massa tincidunt dui ut ornare lectus. Integer feugiat scelerisque varius morbi enim nunc. Bibendum neque egestas congue quisque egestas diam. Cras ornare arcu dui vivamus arcu felis bibendum. Dignissim suspendisse in est ante in nibh mauris. Sed tempus urna et pharetra pharetra massa massa ultricies mi.

Mollis nunc sed id semper risus in. Convallis a cras semper auctor neque. Diam sit amet nisl suscipit. Lacus viverra vitae congue eu consequat ac felis donec. Egestas integer eget aliquet nibh praesent tristique magna sit amet. Eget magna fermentum iaculis eu non diam. In vitae turpis massa sed elementum. Tristique et egestas quis ipsum suspendisse ultrices. Eget lorem dolor sed viverra ipsum. Vel turpis nunc eget lorem dolor sed viverra. Posuere ac ut consequat semper viverra nam. Laoreet suspendisse interdum consectetur libero id faucibus. Diam phasellus vestibulum lorem sed risus ultricies tristique. Rhoncus dolor purus non enim praesent elementum facilisis. Ultrices tincidunt arcu non sodales neque. Tempus egestas sed sed risus pretium quam vulputate. Viverra suspendisse potenti nullam ac tortor vitae purus faucibus ornare. Fringilla urna porttitor rhoncus dolor purus non. Amet dictum sit amet justo donec enim.

Mattis ullamcorper velit sed ullamcorper morbi tincidunt. Tortor posuere ac ut consequat semper viverra. Tellus mauris a diam maecenas sed enim ut sem viverra. Venenatis urna cursus eget nunc scelerisque viverra mauris in. Arcu ac tortor dignissim convallis aenean et tortor at. Curabitur gravida arcu ac tortor dignissim convallis aenean et tortor. Egestas tellus rutrum tellus pellentesque eu. Fusce ut placerat orci nulla pellentesque dignissim enim sit amet. Ut enim blandit volutpat maecenas volutpat blandit aliquam etiam. Id donec ultrices tincidunt arcu. Id cursus metus aliquam eleifend mi.

Tempus quam pellentesque nec nam aliquam sem. Risus at ultrices mi tempus imperdiet. Id porta nibh venenatis cras sed felis eget velit. Ipsum a arcu cursus vitae. Facilisis magna etiam tempor orci eu lobortis elementum. Tincidunt dui ut ornare lectus sit. Quisque non tellus orci ac. Blandit libero volutpat sed cras. Nec tincidunt praesent semper feugiat nibh sed pulvinar proin gravida. Egestas integer eget aliquet nibh praesent tristique magna.





Building a modern, lightning-fast website often comes down to choosing the right toolchain. If your goal is content-driven performance, **Astro** is one of the best frameworks available.
Here is a comprehensive breakdown of how to build and host an Astro website from scratch.
## 1. Why Choose Astro?
Astro uses a unique architecture called **Server-Islands** (previously known as Astro Islands). It renders your HTML entirely on the server and strips away all unused JavaScript by default.
 * **Zero JS by default:** Your pages load instantly because there is no heavy framework overhead.
 * **BYOF (Bring Your Own Framework):** You can use React, Vue, Svelte, or Solid components right inside your Astro templates when you actually need interactivity.
 * **Content-focused:** Perfect for blogs, portfolios, marketing sites, and e-commerce.
## 2. Building Your First Astro Site
Setting up a project takes less than two minutes using the automated CLI tool.
**Initialize the project**
*Requires Node.js v18.14.1 or higher*
Open your terminal, navigate to your workspace, and run the installation command:

Follow the interactive prompts to name your project, choose a template (empty or sample blog), and decide if you want to use TypeScript.**Install dependencies**
*Navigate to project folder*
Move into your newly created project directory and install the required packages:
**Start the local development server**
*Verify setup*
Launch the local development environment to see your site live in the browser:

Open http://localhost:4321 in your browser to view your working template.**Build for production**
*Generate static assets*
When your site is ready, compile your source code into a highly optimized, static deployment package:

This outputs static assets directly into the /dist directory.
## 3. Hosting Options Compared
Because Astro builds down to standard HTML, CSS, and JavaScript, you can host it virtually anywhere for free. The choice depends on whether you are deploying a static site (SSG) or need Server-Side Rendering (SSR).
| Hosting Provider | Deployment Type | Best For | Setup Complexity |
|---|---|---|---|
| **Vercel** | Static & SSR | Seamless framework integration, analytics | Very Low (Git integration) |
| **Netlify** | Static & SSR | Great form handling, redirect rules, split testing | Very Low (Git integration) |
| **GitHub Pages** | Static Only | Open-source portfolios, project documentation | Low (Requires GitHub Actions) |
| **Cloudflare Pages** | Static & SSR | Incredible global CDN edge performance, low latency | Low (Git integration) |
## 4. Deploying Your Project (The Git Workflow)
The most efficient way to host your Astro site is to link your code repository to your hosting provider for continuous deployment.
 1. **Push to GitHub:** Create a repository on GitHub and push your local Astro project code up to it.
 2. **Connect Provider:** Log into your chosen platform (Vercel, Netlify, or Cloudflare Pages) and select **Import Project**.
 3. **Configure Build Settings:** The platform will usually auto-detect Astro, but verify these exact settings:
   * **Build Command:** npm run build
   * **Output Directory:** dist
 4. **Deploy:** Click deploy. Your site will build automatically, and every future git push to your main branch will trigger an instant production update.


********------*********---------*********



Configuring a custom domain and ensuring it is secured with an SSL certificate is the final step in launching your Astro website. Both Vercel and Netlify make this process incredibly straightforward by offering free, automated managed SSL certificates (via Let's Encrypt) as soon as your domain points to their servers.
​Here is the complete guide to configuring your DNS records and SSL for both platforms.
​Step 1: Add the Domain to Your Hosting Dashboard
​Before changing any DNS settings, you must tell your hosting provider which domain to expect.
​On Vercel: Go to your Project Dashboard → Settings → Domains. Type in your domain (e.g., yourdomain.com) and click Add. Vercel will automatically suggest adding both the apex domain (yourdomain.com) and the www subdomain.
​On Netlify: Go to your Site Dashboard → Site configuration → Domain management. Click Add custom domain, enter your domain name, and click Verify and Add domain.
​Once added, both platforms will display the exact DNS records (A, CNAME, or ALIAS) you need to configure at your domain registrar.
​Step 2: Configure Your DNS Records
​Log into the account where you purchased your domain (e.g., Namecheap, GoDaddy, Google Domains/Squarespace, Hover) and navigate to the DNS Management or Advanced DNS panel.
​You need to configure two primary records to ensure your Astro site loads correctly whether a user types yourdomain.com or www.yourdomain.com.
​Option A: If your site is hosted on Vercel
​Create or update the following two records in your registrar's DNS settings:
​The Apex Domain (yourdomain.com):
​Type: A
​Host/Name: @ (or leave blank depending on the registrar)
​Value/Points to: 76.76.21.21
​TTL: Automatic or 3600
​The WWW Subdomain (www.yourdomain.com):
​Type: CNAME
​Host/Name: www
​Value/Points to: cname.vercel-dns.com.
​TTL: Automatic or 3600
​Option B: If your site is hosted on Netlify
​Create or update the following two records in your registrar's DNS settings:
​The Apex Domain (yourdomain.com):
​Recommended: If your registrar supports ALIAS, ANAME, or Flattening records, use that instead of an A record.
​Type: ALIAS or ANAME
​Host/Name: @
​Value: your-site-name.netlify.app
​Alternative (Standard A Record): If your registrar only supports standard A records:
​Type: A
​Host/Name: @
​Value/Points to: 75.2.60.5 (Netlify's load balancer IP)
​The WWW Subdomain (www.yourdomain.com):
​Type: CNAME
​Host/Name: www
​Value/Points to: your-site-name.netlify.app
​(Note: Remember to delete any pre-existing default A or CNAME records pointing to your registrar's placeholder/parking pages, as they will conflict with your new settings).
​Step 3: Provision and Verify SSL
​You do not need to purchase an SSL certificate. Both Vercel and Netlify handle generation, installation, and renewals automatically.
​Wait for DNS Propagation: DNS changes can take anywhere from a few minutes to up to 24-48 hours to propagate globally, though it usually happens within an hour.
​Automatic Generation: * Vercel: Vercel constantly polls your domain status. As soon as it detects the correct DNS records, the status indicator in your dashboard will change from a red warning to a green checkmark, and a Let's Encrypt SSL certificate will automatically issue.
​Netlify: Scroll down to the SSL/TLS status section on the Domain Management page. Once DNS resolves, Netlify will provision the certificate. If it hasn't happened automatically yet, click the Verify DNS configuration or Provision Let's Encrypt certificate button to force a manual check.
​Once complete, your Astro site will automatically force global HTTP-to-HTTPS redirection, ensuring all traffic to your site is encrypted and secure.





