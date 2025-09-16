### Updated Plan Note:

**09/2025 Plan(Week 3): Scheme 1: Kids' Fun Nutrition Guide**

**Direction:** Develop a user-friendly web system for personalized food recommendations tailored for children aged 3-12 and their parents using WordPress, focusing on frontend interaction and recommendation logic. This is part of a collaborative effort with a team of 4 on the "Food Component Detection for Dietary Recommendation" project, emphasizing growth, immunity, and overcoming picky eating habits.

**Outline:**

- **Requirement Analysis & Planning (1-2 months):** Research existing systems (e.g., Keep, MyFitnessPal kids' modules), define user roles (children and parents), and collect a food nutrient database suited for kids. Evaluate WordPress plugins for customization.
- **System Design (1-2 months):** Design frontend using WordPress themes (e.g., child-friendly themes like Divi or Astra), backend leveraging WordPress CMS with custom plugins, database integration (e.g., via WP Data Access or custom MySQL), and a rule-based recommendation algorithm tailored for children's nutritional needs.
- **Implementation & Development (2-3 months):** Build a playful UI with WordPress page builders (e.g., Elementor), custom post types for recipes and goals.
- **Testing & Optimization (1 month):** Functional and performance testing, gather user feedback from parents and kids, optimize plugin performance and load times.
- **Documentation & Presentation (0.5-1 month):** Final report and demo preparation, highlighting the fun and educational aspects, with screenshots of WordPress dashboard and frontend.

**Goals & Requirements:**

- **Functional:**
  - **User Registration:** Email/phone login for parents via WordPress user management, privacy-compliant, with child profile creation (age, weight, preferences) using custom fields or a plugin like Profile Builder.
  - **Health Goal Selection:** Form with kid-specific goals (e.g., growth development, immune boost, overcoming picky eating) using WordPress forms (e.g., WPForms or Gravity Forms)
  - **Food Nutrient Database:** 100+ kid-friendly foods with nutrition data (e.g., bananas, eggs) managed via custom post types or a plugin like Advanced Custom Fields (ACF), searchable with a custom search plugin.
  - **Personalized Recommendation:** 3-5 fun options per goal displayed as custom posts or pages, including animated recipe steps via embedded videos or GIFs, tailored to age (e.g., <1800kcal/day for 4-8 years) using a custom plugin or shortcode.
  - **Nutrition Reports:** Colorful progress bars for "growth points" (e.g., protein +10 points) using WordPress charts plugins (e.g., WP Charts), downloadable PDF for parents with school lunch tips via a plugin like WP PDF Generator.
  - **Compatibility:** Responsive design using a mobile-friendly WordPress theme, optional image integration for future team collaboration via a media upload plugin.

- **Non-Functional:**
  - **Performance:** Load <3s, recommendation <5s, support 10 concurrent users, optimized with caching plugins like W3 Total Cache.
  - **Usability:** WCAG-compliant, intuitive UI with cartoon themes using custom WordPress styling, touch-friendly big buttons, and dual mode (parent/kid) via user role management.
  - **Security:** HTTPS, encrypted data with WordPress security plugins (e.g., Wordfence), no ads, strict privacy for child data accessible only by parents using role-based access.
  - **Maintainability:** Modular code with WordPress best practices, Git version control for theme/plugin development.

