MovieRecommenderProject/
│
├── model/                  # Plain Java objects representing data
│   ├── User.java           # User entity (username, hashed password, salt)
│   ├── Movie.java          # Movie entity (id, title, metadata)
│   └── Rating.java         # Rating entity (user, movie, score)
│
├── util/                   # Utility/helper classes
│   └── PasswordUtil.java   # Password hashing and salting functions
│
├── service/                # Business logic & algorithms
│   ├── UserService.java    # User management (signup, login)
│   ├── MovieService.java   # Movie management (browse, search)
│   ├── RatingService.java  # Manage ratings (add, update)
│   └── RecommendationService.java # Recommendation algorithms (CF, content-based)
│
├── cli/                    # CLI user interaction & menus
│   └── CLIApp.java         # Main CLI program entry point
│
└── Main.java               # Program launcher calling CLIApp.main()
