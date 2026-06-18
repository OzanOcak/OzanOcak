┌─────────────────────────────────────────────────────────────────────────────────────────────┐
│                              FULL STACK APPLICATION                                         │
│                              Live 1.5 years · 1500+ visitors                                │
├─────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                             │
│  ┌──────────────────────────────────────────────────────────────────────────────────────┐   │
│  │                              FRONTEND (Vercel)                                       │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │                           Next.js 14 (App Router)                            │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         App Directory (Pages)                           │ │    │   │
│  │  │  │  ├── (public-auth)  → Login, Signup, Verify OTP, Forgot Password        │ │    │   │
│  │  │  │  ├── (private)      → Profile, Admin Dashboard, User Management         │ │    │   │
│  │  │  │  ├── (public)       → Blog Feed, Blog Post (static generation)          │ │    │   │
│  │  │  │  └── api/           → (Optional) Vercel API routes                      │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Components (50+ Files)                          │ │    │   │
│  │  │  │  ├── auth/         → Login, Signup, Email, Password Reset               │ │    │   │
│  │  │  │  ├── oauth/        → Google Signin, OAuth Callback Handler              │ │    │   │
│  │  │  │  ├── navigation/   → NavBar, MobileNav, ThemeToggle, ProfileMenu        │ │    │   │
│  │  │  │  ├── sidesheet/    → Comment System (CRUD + Likes)                      │ │    │   │
│  │  │  │  ├── blogpost/     → ContentTable, SideBar, Tags, LikePost              │ │    │   │
│  │  │  │  ├── admin/        → BlogTable, UserTable, SearchBox                    │ │    │   │
│  │  │  │  ├── ui/           → shadcn/ui (Accordion, Avatar, Button, etc.)        │ │    │   │
│  │  │  │  └── custom/       → AlertBox, ErrorBoundary, Layout, Providers         │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Hooks (36+ Files)                               │ │    │   │
│  │  │  │  ├── auth/          → useLogin, useLogout, useSignup, useOtpVerify      │ │    │   │
│  │  │  │  ├── oauth/         → useGoogleSignin, useOauthLogin                    │ │    │   │
│  │  │  │  ├── roles/         → Admin (5) + User (3) hooks                        │ │    │   │
│  │  │  │  ├── bloglikes/     → useLike, useDislike, useGetLikes                  │ │    │   │
│  │  │  │  ├── blogpublish/   → useHandlePublish, useHandleUnpublish              │ │    │   │
│  │  │  │  ├── comments/      → Create, Delete, Edit, Fetch, Like, Unlike (7)     │ │    │   │
│  │  │  │  ├── sessions/      → InactivityTimeout, RouteTracker, SessionChecker   │ │    │   │
│  │  │  │  └── visitcount/    → useGetVisitCounts, useIncreaseVisitCount          │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         State Management                                │ │    │   │
│  │  │  │  ├── React Query    → Server state, caching, background refetch         │ │    │   │
│  │  │  │  └── Zustand        → Client state (Auth, User, Client slices)          │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Axios Interceptor                               │ │    │   │
│  │  │  │  • Silent token refresh on 401                                          │ │    │   │
│  │  │  │  • Request queuing during refresh                                       │ │    │   │
│  │  │  │  • Automatic retry after refresh                                        │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  • Framework: Next.js 14 (React 18)                                                  │   │
│  │  • Language: TypeScript                                                              │   │
│  │  • Styling: Tailwind CSS + shadcn/ui                                                 │   │
│  │  • Hosting: Vercel (Auto-deploy from GitHub)                                         │   │
│  │                                                                                      │   │
│  └──────────────────────────────────────────────────────────────────────────────────────┘   │
│                                          │                                                  │
│                                          │ HTTPS (REST API)                                 │
│                                          │ via Cloudflare                                   │
│                                          ▼                                                  │
│  ┌──────────────────────────────────────────────────────────────────────────────────────┐   │
│  │                            BACKEND (Raspberry Pi)                                    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │                        Express.js Server (Node.js)                           │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Middleware (9 Files)                            │ │    │   │
│  │  │  │  ├── authenticate-user.ts     → JWT verification, sets req.userId       │ │    │   │
│  │  │  │  ├── authorize-user.ts        → RBAC permission check                   │ │    │   │
│  │  │  │  ├── validate-user.ts         → Zod validation (email/password)         │ │    │   │
│  │  │  │  ├── ip-rate-limiter.ts       → 40 req / 15 min per IP                  │ │    │   │
│  │  │  │  ├── comment-rate-limiter.ts  → 20 req / 15 min (comments)              │ │    │   │
│  │  │  │  ├── like-rate-limiter.ts     → 20 req / 15 min (likes)                 │ │    │   │
│  │  │  │  ├── email-rate-limiter.ts    → 20 req / 15 min (email-based)           │ │    │   │
│  │  │  │  ├── track-visit.ts           → Cookie-based visitor tracking           │ │    │   │
│  │  │  │  └── csp-header.ts            → Content Security Policy headers         │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Routes (6 Files)                                │ │    │   │
│  │  │  │  ├── authRoutes.ts      → /signup, /login, /refresh, /logout            │ │    │   │
│  │  │  │  ├── oauthRoutes.ts     → /oauth/url, /oauth/callback, /oauth/ologin    │ │    │   │
│  │  │  │  ├── roleRoutes.ts      → /profile, /admin, /admin/:userId              │ │    │   │
│  │  │  │  ├── commentRoutes.ts   → /posts/:postId/comments (CRUD + likes)        │ │    │   │
│  │  │  │  ├── likeblogRoutes.ts  → /blogpost/:postId/likeblog (like/unlike)      │ │    │   │
│  │  │  │  └── visitRoutes.ts     → /visit-count, /increase-visit-count           │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Controllers (33 Files)                          │ │    │   │
│  │  │  │  ├── Auth (8)       → Login, Logout, Refresh, Register, Verify, Reset   │ │    │   │
│  │  │  │  ├── OAuth (3)      → OAuth URL, Callback, Login                        │ │    │   │
│  │  │  │  ├── Admin (7)      → DeleteUser, UpdateRole, Publish, Unpublish        │ │    │   │
│  │  │  │  ├── User (3)       → Profile, UpdateName, DeleteSelf                   │ │    │   │
│  │  │  │  ├── Comments (7)   → Create, Delete, Edit, Fetch, Like, Unlike, Count  │ │    │   │
│  │  │  │  ├── Blog Likes (3) → GetLikes, Like, Dislike                           │ │    │   │
│  │  │  │  └── Visit (2)      → GetCount, Increment                               │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         Services (7 Files)                              │ │    │   │
│  │  │  │  ├── deleteProfile.ts    → Delete user account                          │ │    │   │
│  │  │  │  ├── deleteSelfProfile.ts→ Delete own account                           │ │    │   │
│  │  │  │  ├── updateRole.ts       → Update user role (admin only)                │ │    │   │
│  │  │  │  ├── updateName.ts       → Update username                              │ │    │   │
│  │  │  │  ├── getAllUsers.ts      → Paginated user list with search              │ │    │   │
│  │  │  │  ├── countUsers.ts       → Total user count with filters                │ │    │   │
│  │  │  │  └── getUserProfile.ts   → Profile with OAuth picture                   │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │                         OTP Storage (In-Memory)                         │ │    │   │
│  │  │  │  • unverifiedUsers: Record<string, UserTemp>                            │ │    │   │
│  │  │  │  • 5-minute TTL per OTP                                                 │ │    │   │
│  │  │  │  • Auto-cleanup with setTimeout                                         │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  • Framework: Express.js (Node.js 20+)                                               │   │
│  │  • Language: TypeScript                                                              │   │
│  │  • Auth: JWT (Access 15min / Refresh 5d) + OAuth 2.0 (PKCE)                          │   │
│  │  • Hosting: Raspberry Pi 4 (8GB) + Cloudflare (Reverse Proxy + SSL)                  │   │
│  │                                                                                      │   │
│  └──────────────────────────────────────────────────────────────────────────────────────┘   │
│                                          │                                                  │
│                                          │ SQL / Drizzle                                    │
│                                          ▼                                                  │
│  ┌──────────────────────────────────────────────────────────────────────────────────────┐   │
│  │                             DATABASE (PostgreSQL)                                    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │                         Tables (6)                                           │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │  users                                                                  │ │    │   │
│  │  │  │  ├── id: SERIAL PK                                                      │ │    │   │
│  │  │  │  ├── username: VARCHAR(50) NOT NULL                                     │ │    │   │
│  │  │  │  ├── email: VARCHAR(255) UNIQUE NOT NULL                                │ │    │   │
│  │  │  │  ├── password: VARCHAR(255) NULL (nullable for OAuth)                   │ │    │   │
│  │  │  │  ├── role: VARCHAR(20) DEFAULT 'user'                                   │ │    │   │
│  │  │  │  ├── created_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  │  └── updated_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │  tokens                                                                 │ │    │   │
│  │  │  │  ├── id: SERIAL PK                                                      │ │    │   │
│  │  │  │  ├── userId: INT FK → users.id ON DELETE CASCADE                        │ │    │   │
│  │  │  │  ├── tokenId: UUID NOT NULL UNIQUE (refresh token ID)                   │ │    │   │
│  │  │  │  └── created_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │  oauth_identities                                                       │ │    │   │
│  │  │  │  ├── id: SERIAL PK                                                      │ │    │   │
│  │  │  │  ├── userId: INT FK → users.id ON DELETE CASCADE                        │ │    │   │
│  │  │  │  ├── provider: VARCHAR(50) NOT NULL (google, github, etc.)              │ │    │   │
│  │  │  │  ├── providerUserId: VARCHAR(255) NOT NULL                              │ │    │   │
│  │  │  │  ├── profilePicture: VARCHAR(255) NULL                                  │ │    │   │
│  │  │  │  └── created_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │  comments                                                               │ │    │   │
│  │  │  │  ├── id: SERIAL PK                                                      │ │    │   │
│  │  │  │  ├── content: TEXT NOT NULL                                             │ │    │   │
│  │  │  │  ├── userId: INT FK → users.id ON DELETE CASCADE                        │ │    │   │
│  │  │  │  ├── blogId: VARCHAR(255) NOT NULL (post slug)                          │ │    │   │
│  │  │  │  ├── likeCount: INT DEFAULT 0                                           │ │    │   │
│  │  │  │  ├── createdAt: TIMESTAMP DEFAULT NOW()                                 │ │    │   │
│  │  │  │  └── updatedAt: TIMESTAMP DEFAULT NOW()                                 │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │  likes                                                                  │ │    │   │
│  │  │  │  ├── id: SERIAL PK                                                      │ │    │   │
│  │  │  │  ├── slug: VARCHAR(255) UNIQUE NOT NULL (post slug)                     │ │    │   │
│  │  │  │  ├── likes_count: INT DEFAULT 0                                         │ │    │   │
│  │  │  │  └── created_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  │                                                                              │    │   │
│  │  │  ┌─────────────────────────────────────────────────────────────────────────┐ │    │   │
│  │  │  │  website_visits                                                         │ │    │   │
│  │  │  │  ├── id: SERIAL PK (always 1 - singleton)                               │ │    │   │
│  │  │  │  ├── total_visits: INT DEFAULT 0                                        │ │    │   │
│  │  │  │  ├── created_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  │  └── updated_at: TIMESTAMP DEFAULT NOW()                                │ │    │   │
│  │  │  └─────────────────────────────────────────────────────────────────────────┘ │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  • ORM: Drizzle (TypeScript-first)                                                   │   │
│  │  • Hosting: Running on Raspberry Pi (same machine as backend)                        │   │
│  │  • Backup: pg_dump scheduled                                                         │   │
│  │                                                                                      │   │
│  └──────────────────────────────────────────────────────────────────────────────────────┘   │
│                                                                                             │
├─────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                             │
│  ┌──────────────────────────────────────────────────────────────────────────────────────┐   │
│  │                         DEPLOYMENT & INFRASTRUCTURE                                  │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  Cloudflare                                                                  │    │   │
│  │  │  • SSL/TLS Termination (HTTPS)                                               │    │   │
│  │  │  • Reverse Proxy (hides Raspberry Pi IP)                                     │    │   │
│  │  │  • CDN Caching (static assets)                                               │    │   │
│  │  │  • DNS Management (custom domain)                                            │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  Raspberry Pi 4 (8GB RAM)                                                    │    │   │
│  │  │  • OS: Raspberry Pi OS (Linux)                                               │    │   │
│  │  │  • Backend: Node.js 20+ (PM2 for process management)                         │    │   │
│  │  │  • Database: PostgreSQL 16                                                   │    │   │
│  │  │  • Docker (optional, for containerization)                                   │    │   │
│  │  │  • Uptime: 1.5 years                                                         │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  Vercel                                                                      │    │   │
│  │  │  • Frontend Hosting                                                          │    │   │
│  │  │  • Auto-deploy from GitHub                                                   │    │   │
│  │  │  • Edge Network (fast global delivery)                                       │    │   │
│  │  │  • Environment Variables (API_URL, secrets)                                  │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  └──────────────────────────────────────────────────────────────────────────────────────┘   │
│                                                                                             │
├─────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                             │
│  ┌──────────────────────────────────────────────────────────────────────────────────────┐   │
│  │                         AUTHENTICATION & SECURITY FLOW                               │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  1. Login (Email/Password or Google OAuth)                                   │    │   │
│  │  │     ├── Validate credentials (bcrypt compare)                                │    │   │
│  │  │     ├── Generate Access Token (JWT, 15min expiry)                            │    │   │
│  │  │     ├── Generate Refresh Token (JWT, 5d expiry) + Token ID (UUID)            │    │   │
│  │  │     ├── Store Token ID in tokens table                                       │    │   │
│  │  │     └── Return Access Token (header) + Refresh Token (httpOnly cookie)       │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  2. Token Refresh (Silent)                                                   │    │   │
│  │  │     ├── Axios interceptor catches 401                                        │    │   │
│  │  │     ├── POST /api/refresh with Refresh-Token-ID header                       │    │   │
│  │  │     ├── Verify Refresh Token (JWT secret)                                    │    │   │
│  │  │     ├── Check Token ID exists in tokens table                                │    │   │
│  │  │     ├── Generate new tokens (rotation)                                       │    │   │
│  │  │     ├── Delete old Token ID, insert new Token ID                             │    │   │
│  │  │     └── Retry original request with new Access Token                         │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  3. OAuth (Google) with PKCE                                                 │    │   │
│  │  │     ├── /oauth/url → Generate PKCE challenge + state, redirect to Google     │    │   │
│  │  │     ├── /oauth/callback → Exchange code for tokens, fetch profile            │    │   │
│  │  │     ├── /oauth/ologin → Create/update user, generate app tokens              │    │   │
│  │  │     └── Return Access Token (header) + Refresh Token (httpOnly cookie)       │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  │  ┌──────────────────────────────────────────────────────────────────────────────┐    │   │
│  │  │  4. Authorization (RBAC)                                                     │    │   │
│  │  │     ├── authenticate.ts → Verify JWT, attach user to req                     │    │   │
│  │  │     ├── authorize.ts → Check permissions against roles config                │    │   │
│  │  │     ├── Admin: view_profile, view_users, edit_user_role, delete_user,        │    │   │
│  │  │     │           publish_post, unpublish_post, create_comment, like_comment   │    │   │
│  │  │     ├── Editor: view_profile, view_users                                     │    │   │
│  │  │     └── User: view_profile, edit_self_user_name, delete_self_user,           │    │   │
│  │  │                 create_comment, like_comment, edit_comment, delete_comment   │    │   │
│  │  └──────────────────────────────────────────────────────────────────────────────┘    │   │
│  │                                                                                      │   │
│  └──────────────────────────────────────────────────────────────────────────────────────┘   │
│                                                                                             │
├─────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                             │
│  ┌──────────────────────────────────────────────────────────────────────────────────────┐   │
│  │                                    DATA FLOW                                         │   │
│  │                                                                                      │   │
│  │  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐     │   │
│  │  │  User        │────▶│  Frontend    │────▶│  Backend     │────▶│  Database    │     │   │
│  │  │  (Browser)   │     │  (Vercel)    │     │  (Raspberry  │     │  (Postgres)  │     │   │
│  │  └──────────────┘     └──────────────┘     │   Pi)        │     └──────────────┘     │   │
│  │                                            └──────────────┘                          │   │
│  │                                                                                      │   │
│  │  Example: User views blog post with comments                                         │   │
│  │  ───────────────────────────────────────────────────────────────────────             │   │
│  │  1. GET /api/posts/my-post/comments (Frontend → Backend)                             │   │
│  │  2. Backend queries: SELECT * FROM comments WHERE blogId = 'my-post'                 │   │
│  │  3. Backend queries: SELECT username, profilePicture FROM users JOIN oauth           │   │
│  │  4. Backend returns JSON → Frontend renders comments                                 │   │
│  │                                                                                      │   │
│  │  Example: User likes a comment                                                       │   │
│  │  ───────────────────────────────────────────────────────────────────────             │   │
│  │  1. POST /api/comments/123/likecomment (Frontend → Backend)                          │   │
│  │  2. authenticate.ts → Verify JWT                                                     │   │  
│  │  3. authorize.ts → Check 'like_comment' permission                                   │   │  
│  │  4. Controller: UPDATE comments SET likeCount = likeCount + 1 WHERE id = 123         │   │  
│  │  5. Backend returns updated comment → Frontend updates UI                            │   │  
│  │                                                                                      │   │
│  └──────────────────────────────────────────────────────────────────────────────────────┘   │
│                                                                                             │
└─────────────────────────────────────────────────────────────────────────────────────────────┘
