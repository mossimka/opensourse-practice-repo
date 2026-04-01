# OpenSource Practice Repo

A modern iOS starter repository for learning, collaboration, and shipping features quickly.

## Features

- iOS project setup with scalable structure
- Unit-test ready
- CLI build/test support
- Open-source friendly contribution flow

## Requirements

- macOS
- Xcode 15+
- Swift 5.9+
- Git

## Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/opensourse-practice-repo.git
   cd opensourse-practice-repo
   ```

2. Open in Xcode:

   ```bash
   open *.xcodeproj
   # or if your project uses CocoaPods:
   open *.xcworkspace
   ```

3. Build from terminal (optional):

   ```bash
   xcodebuild -scheme <YourScheme> -destination 'platform=iOS Simulator,name=iPhone 15' build
   ```

## Running the App

- Open project in Xcode
- Choose a simulator/device
- Press `Cmd + R`

## Testing

In Xcode: `Cmd + U`

From terminal:

```bash
xcodebuild test -scheme <YourScheme> -destination 'platform=iOS Simulator,name=iPhone 15'
```

## Project Structure

```text
.
├── App/            # App entry point, scenes, navigation
├── Core/           # Shared services, models, utilities
├── Resources/      # Assets, localization, configs
├── Tests/          # Unit and integration tests
└── README.md
```

## Contributing

1. Fork the repository
2. Create a feature branch:

   ```bash
   git checkout -b feature/my-feature
   ```

3. Commit:

   ```bash
   git commit -m "feat: add my feature"
   ```

4. Push and open a Pull Request

## License

MIT — see `LICENSE`.

## Roadmap

- [ ] CI pipeline
- [ ] UI tests
- [ ] Release automation
- [ ] Architecture docs
