# Umbilo Car Wash & Shisanyama Website

## Web Development — WEDE5020

**Student:** Sinethemba Dlamini
**Student Number:** ST10517682
**Module:** DNM0601



##  Project Overview

This project involves the design and development of a responsive website for **Umbilo Car Wash & Shisanyama**, a Durban-based business that combines professional car-washing services with an authentic South African shisanyama experience.

The website is designed to improve the business's online presence, provide customers with easy access to information, and make it easier for customers to book services and explore the food menu.

##  Organisation

### Umbilo Car Wash & Shisanyama

The business started as a small roadside car wash in Umbilo, Durban. It later developed into a lifestyle destination combining vehicle valeting, braai cuisine, music, and community entertainment.

### Mission

To provide reliable vehicle valeting and authentic, high-quality braai cuisine in a clean, vibrant, and welcoming environment.

### Vision

To become a leading Durban lifestyle destination where automotive care meets township culture and community hospitality.

### Target Audience

* Umbilo residents and working professionals
* Local commuters and motorists
* Weekend socialisers
* Braai enthusiasts and music lovers
* Customers looking for event or group venues


##  Website Goals

The main objectives of the website are to:

* Increase the business's digital visibility.
* Provide customers with accurate business information.
* Display car wash packages and pricing.
* Display the shisanyama menu.
* Allow customers to make bookings and enquiries.
* Provide operating hours and location information.
* Reduce customer waiting times through online reservations.
* Promote events and social media activity.

### Key Performance Indicators

The website's success can be measured through:

* Monthly website visitors.
* Local search traffic.
* Online booking conversions.
* Menu page engagement.
* Customer enquiries.
* Engagement with event announcements.

---

##  Current Website Analysis

### Strengths

* Strong word-of-mouth reputation.
* Existing social media engagement.
* Unique combination of car washing and shisanyama.
* Strong local community appeal.

### Weaknesses

The business lacks a centralised website, which can make it difficult for customers to find:

* Current menu prices.
* Car wash packages.
* Operating hours.
* Exact location details.
* Booking and enquiry information.

### Proposed Improvements

The new website addresses these issues by providing:

* An interactive menu.
* Clear service pricing.
* Online booking and enquiry forms.
* Google Maps integration.
* Contact information.
* Links to social media platforms.

---

##  Website Features

### Homepage

A visually engaging landing page featuring the car wash, food, and social atmosphere, with clear calls-to-action such as **"Book a Wash"** and **"View Menu"**.

### About Us

Information about the history of Umbilo Car Wash & Shisanyama and its development from a small roadside business into a local lifestyle destination.

### Services & Menu

The website will include:

**Car Wash Services**

* Express Wash
* Full Valet
* Executive Polish

**Shisanyama Menu**

* Meat selections
* Pap
* Chakalaka
* Salads
* Coleslaw
* Beverages
* Custom platter options

### Bookings & Reservations

Customers can submit bookings for premium car wash services or reserve tables for groups and weekend events.

### Contact & Location

The contact section includes:

* Contact details
* Click-to-call functionality
* Operating hours
* Social media links
* Google Maps location and directions

---

##  Location & Side Map

The website will include a **side-by-side location section** so customers can view the business information and map at the same time.

### Location Section

| Business Information                           | Map                                           |
| ---------------------------------------------- | --------------------------------------------- |
| **Umbilo Car Wash & Shisanyama**               |  Google Maps                               |
|  Umbilo, Durban, KwaZulu-Natal, South Africa | Interactive map showing the business location |
|  Click-to-call                               |  Location marker                            |
|  Opening Hours                               |  Directions                                 |
|  Social Media Links                          |  Zoom and navigation                        |



The map should be **responsive**, changing from a two-column layout on desktop screens to a stacked layout on mobile devices.

### Google Maps Integration

The final website can use a Google Maps iframe or Google Maps API. The map should be configured with the **verified business address or coordinates** once these are available.

Example implementation:

```html
<div class="location-section">
    <div class="contact-info">
        <h2>Visit Us</h2>
        <h3>Umbilo Car Wash & Shisanyama</h3>

        <p> Umbilo, Durban, KwaZulu-Natal</p>
        <p> Contact us for bookings</p>
        <p> Check our opening hours</p>

        <a href="#" class="btn">Get Directions</a>
    </div>

    <div class="map-container">
        <iframe
            src="YOUR_GOOGLE_MAPS_EMBED_URL"
            width="100%"
            height="400"
            style="border:0;"
            allowfullscreen=""
            loading="lazy">
        </iframe>
    </div>
</div>
```

### Responsive CSS

```css
.location-section {
    display: grid;
    grid-template-columns: 1fr 1.5fr;
    gap: 30px;
    align-items: stretch;
}

.contact-info {
    background-color: #292929;
    color: white;
    padding: 30px;
    border-radius: 10px;
}

.map-container {
    min-height: 400px;
}

.map-container iframe {
    width: 100%;
    height: 100%;
    min-height: 400px;
    border-radius: 10px;
}

@media (max-width: 768px) {
    .location-section {
        grid-template-columns: 1fr;
    }

    .map-container iframe {
        min-height: 300px;
    }
}
```

---

##  Design & User Experience

The website follows a **modern, mobile-first design**.

### Colour Scheme

* **Flame Orange** — represents fire, braai, and energy.
* **Charcoal** — represents the automotive industry and modern styling.
* **White** — represents cleanliness.
* **Foam Blue** — represents water and the car wash.

### Typography

* **Headings:** Montserrat
* **Body text:** Open Sans or Roboto

### Layout

The website uses:

* Responsive layouts.
* Hero imagery.
* Service cards.
* Clear navigation.
* Prominent call-to-action buttons.
* Flexbox and CSS Grid.
* A side-by-side contact and map section.

### UX Considerations

The website is designed for:

* One-handed mobile navigation.
* Fast loading on mobile networks.
* Clear visual hierarchy.
* Accessible colour contrast.
* Simple and intuitive navigation.
* Easy access to location and directions.

---

##  Technical Requirements

### Domain

`www.umbilocarwash.co.za`

### Technologies

* HTML5
* CSS3
* JavaScript (ES6+)
* Bootstrap 5 or Tailwind CSS
* Flexbox
* CSS Grid
* Google Maps Embed/API

### Hosting

The proposed website will use South African Linux-based hosting, such as xneelo or Domains.co.za, to provide suitable local performance and hosting support.

---

##  Development Timeline

| Phase   | Milestone                                        | Duration      |
| ------- | ------------------------------------------------ | ------------- |
| Phase 1 | Requirements, content collection and wireframing | Week 1        |
| Phase 2 | UI/UX design and front-end development           | Week 2        |
| Phase 3 | Form integration, maps and mobile optimisation   | Week 3        |
| Phase 4 | Testing, quality assurance and client review     | Week 4        |
| Phase 5 | Final deployment and domain launch               | End of Week 4 |

---

##  Estimated Budget

| Item                         |              Cost |
| ---------------------------- | ----------------: |
| Domain Registration          |            R99.00 |
| Web Hosting                  |     R120.00/month |
| Website Design & Development |         R6,500.00 |
| SSL Certificate              |             R0.00 |
| Content & Photography        |         R1,500.00 |
| Maintenance                  |     R350.00/month |
| **Estimated Initial Total**  |     **R8,099.00** |
| **Monthly Recurring Cost**   | **R470.00/month** |

---

##  References

1. IIE Rosebank College. (2026). *Web Development (WED5112) Portfolio of Evidence (PoE) Guide*. The Independent Institute of Education (Pty) Ltd.
2. Mchunu, S. (2022). *Township Economy and the Rise of Lifestyle Car Washes in KwaZulu-Natal*. Journal of Southern African Cultural Studies, 14(2), 45–58.
3. South African Tourism. (2024). *Shisanyama Culture: Experiencing the Heart of South African Hospitality*.
4. xneelo. (2026). *Web Hosting and .co.za Domain Pricing Structures*.

---

##  Conclusion

The Umbilo Car Wash & Shisanyama website aims to create a professional digital presence for the business while making its services, menu, location, and booking options easily accessible to customers.

The responsive website will combine **automotive services, South African food culture, and community hospitality** into a user-friendly online experience.

The addition of an interactive **side map** will make it easier for customers to locate the business, obtain directions, and plan their visit, particularly for new customers and visitors to the Umbilo area.
