
## FRONTEND Components 
Pages/UI: pages (tickets, dashboard, admin, analytics)
Components: components (React components like FollowerSelector, layout components, modals)
Hooks: hooks (useTickets, useComments, useSelecoes, etc.)
Contexts: contexts (ThemeContext, PerfilVisualContext)
Styles: styles (global CSS, theme)
UI Libraries: Ant Design, React Query, 

## BACKEND Components (Will move to NestJS)
### API Routes: api
api/tickets/ - ticket CRUD operations
api/comentarios/ - comments
api/admin/ - admin management
api/keycloak/ - user management
api/selecoes/ - selections/dropdowns
api/upload/ - file uploads
api/auth/ - authentication endpoints

### Business Logic: libs
libs/prisma/ - database client
libs/api/ - API utilities (jira, ticket helpers, response handlers)
libs/auth/ - authentication logic
libs/keycloak/ - Keycloak integration
### Database:
Prisma ORM with SQLite
Schema: schema.prisma (Chamado, Software, Modulo, ProductLine, etc.)
Migrations in migrations