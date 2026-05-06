# Fidus CRM - Executive-Grade Sales Management System

A modern, real-time CRM platform built with React for global sales teams. Multi-tenant architecture with advanced pipeline management, custom reporting, and real-time collaboration.

## Features

### 🏢 Core Modules
- **Dashboard**: Real-time KPIs and mission control view
- - **Leads Management**: Contact registry with advanced filtering
  - - **Pipeline**: Drag-and-drop Kanban pipeline management
    - - **Reports**: Custom analytics with 6+ visualization types
      - - **Tasks**: Reminder-based task management
        - - **Landing Page**: Marketing-ready landing with beta signup
         
          - ### 🎨 Design & UX
          - - **Dark Theme**: Professional dark mode with blue/violet accent colors
            - - **Responsive**: Full-screen responsive design
              - - **Animated Components**: Cosmic SVG animations (Earth, Saturn)
                - - **Smooth Transitions**: Modern animations and transitions
                  - - **Accessibility**: Semantic HTML and ARIA labels
                   
                    - ### 💼 Business Features
                    - - **Multi-Region Support**: DACH, EU, LATAM
                      - - **Multi-Currency**: Euro (€) support
                        - - **Global Teams**: Support for international sales reps
                          - - **Real-Time Sync**: Live pipeline updates
                            - - **Custom KPIs**: Build your own metrics
                             
                              - ## Technology Stack
                             
                              - - **Frontend**: React 18.2.0
                                - - **Build Tool**: Vite 4.3.9
                                  - - **Styling**: Inline CSS with design tokens
                                    - - **State Management**: React Hooks (useState, useEffect, useMemo)
                                     
                                      - ## Getting Started
                                     
                                      - ### Installation
                                     
                                      - ```bash
                                        # Clone repository
                                        git clone https://github.com/altnt93/fidus-crm-react.git
                                        cd fidus-crm-react

                                        # Install dependencies
                                        npm install

                                        # Start development server
                                        npm run dev

                                        # Build for production
                                        npm run build
                                        ```

                                        ### Project Structure

                                        ```
                                        fidus-crm-react/
                                        ├── package.json
                                        ├── src/
                                        │   └── App.jsx          # Main React component
                                        └── README.md
                                        ```

                                        ## Demo Data

                                        The application includes sample CRM data with:
                                        - 12 leads across multiple regions
                                        - - 7 pipeline stages (New → Won/Lost)
                                          - - 3 sales representatives
                                            - - Historical data spanning 200+ days
                                             
                                              - ## Configuration
                                             
                                              - ### Design Tokens
                                              - All colors and styling are centralized in the `T` object within `App.jsx`:
                                             
                                              - ```javascript
                                                const T = {
                                                  bgDeep: "#03040c",
                                                  accent: "#4f8ef7",
                                                  success: "#10b981",
                                                  // ... more tokens
                                                };
                                                ```

                                                ### Navigation Items
                                                Customize sidebar navigation in the `NAV` array:

                                                ```javascript
                                                const NAV = [
                                                  { id: "dashboard", icon: "⬡", label: "Dashboard" },
                                                  // ... more items
                                                ];
                                                ```

                                                ## Free Deployment Options

                                                ### GitHub Pages
                                                1. Enable GitHub Pages in repository settings
                                                2. 2. Set source to `main` branch
                                                   3. 3. Site available at `https://altnt93.github.io/fidus-crm-react`
                                                     
                                                      4. ### Vercel
                                                      5. ```bash
                                                         npm install -g vercel
                                                         vercel
                                                         ```

                                                         ### Netlify
                                                         1. Connect GitHub repository
                                                         2. 2. Build command: `npm run build`
                                                            3. 3. Publish directory: `dist`
                                                              
                                                               4. ## License
                                                              
                                                               5. MIT - Free to use and modify
                                                              
                                                               6. ## Support
                                                              
                                                               7. For issues and feature requests, visit the [GitHub Issues page](https://github.com/altnt93/fidus-crm-react/issues).
                                                              
                                                               8. ---
                                                              
                                                               9. **Built with React 18 • Vite • Modern CSS**
