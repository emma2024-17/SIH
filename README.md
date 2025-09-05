# SIH
BlueCarbonMRV/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/bluecarbonmrv/
│   │   │   │   ├── data/                # Data layer
│   │   │   │   │   ├── api/             # Retrofit interfaces
│   │   │   │   │   ├── models/          # Data classes (Project, MonitoringEvent, etc.)
│   │   │   │   │   └── repository/      # Handles API <-> ViewModel
│   │   │   │   │
│   │   │   │   ├── ui/                  # UI layer
│   │   │   │   │   ├── main/            # MainActivity, Navigation
│   │   │   │   │   ├── auth/            # Login/Register
│   │   │   │   │   ├── project/         # Project list + details
│   │   │   │   │   ├── monitoring/      # Capture data (GPS, photos, forms)
│   │   │   │   │   └── dashboard/       # Credits summary, history
│   │   │   │   │
│   │   │   │   ├── utils/               # Helpers (Location, Camera, QR)
│   │   │   │   ├── viewmodel/           # ViewModels for UI
│   │   │   │   └── BlueCarbonApp.kt     # Application class
│   │   │   │
│   │   │   ├── res/
│   │   │   │   ├── layout/              # XML layouts
│   │   │   │   ├── values/              # colors.xml, strings.xml, styles.xml
│   │   │   │   ├── drawable/            # App icons, vector assets
│   │   │   │   └── mipmap/              # Launcher icons
│   │   │   │
│   │   │   └── AndroidManifest.xml
│   │   │
│   │   └── test/                        # Unit tests
│   │   └── androidTest/                 # Instrumented tests
│   │
│   ├── build.gradle
│   └── proguard-rules.pro
│
└── build.gradle
