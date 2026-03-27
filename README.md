# SoCal Gig Intelligence & Automation System

Real-time gig offer monitoring and profit-driven decision system for Southern California.

## Quick Start

### Local Development

```bash
# Clone and setup
git clone https://github.com/stomper29SoCal/gig-intelligence-system.git
cd gig-intelligence-system

# Install dependencies
npm install

# Setup environment
cp .env.example .env

# Start services (Docker required)
docker-compose up -d

# Run migrations
npx prisma migrate dev

# Start development server
npm run dev
