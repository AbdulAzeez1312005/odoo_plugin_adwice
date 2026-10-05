adwice_odoo_modules/
│
├── adwice_base/                 → Core Adwice functionality
│   ├── adwice_sdk/              → API communication
│   ├── controllers/             → HTTP endpoints
│   ├── data/                    → Scheduled jobs
│   ├── models/                  → Business logic/data
│   ├── security/                → Access control
│   ├── static/                  → Module assets
│   ├── tests/                   → Odoo tests
│   ├── views/                   → User interface
│   └── wizard/                  → Guided user actions
│
├── adwice_ads/                  → Advertising functionality
│   ├── data/                    → Scheduled advertising jobs
│   ├── models/                  → Campaigns & reports
│   ├── security/                → Advertising permissions
│   ├── static/                  → Module assets
│   ├── tests/                   → Ads tests
│   └── views/                   → Ads UI
│
└── tests_standalone/            → Independent SDK testing
