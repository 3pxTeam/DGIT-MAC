# DGit GUI 🎨

[DGit CLI](https://github.com/3pxTeam/DGIT-CLI) 디자인 파일 전용 버전 관리 시스템을 위한 아름답고 네이티브한 macOS 스타일 데스크탑 인터페이스입니다.

![DGit GUI Screenshot](https://github.com/user-attachments/assets/f61e62e9-9f35-48ca-83fc-9367ec183dbe)


## ✨ 주요 기능

### 🖥️ 네이티브 macOS 경험
- **신호등 컨트롤**: 정통 macOS 윈도우 컨트롤 (닫기, 최소화, 최대화)
- **네이티브 스타일링**: 시스템 폰트와 정통 macOS 디자인 언어를 사용한 다크 테마
- **부드러운 애니메이션**: 인터페이스 전반에 걸친 유동적인 전환과 호버 효과
- **키보드 단축키**: 완전한 macOS 키보드 단축키 지원

### 🎨 디자인 파일 관리
- **비주얼 파일 브라우저**: 타입별 아이콘으로 디자인 파일 탐색 및 관리
- **스마트 파일 감지**: PSD, AI, Sketch, Figma, XD 파일 자동 인식
- **파일 통계**: 실시간 프로젝트 통계 및 파일 개수 표시
- **Finder 연동**: macOS Finder에서 파일에 빠르게 접근

### 🚀 버전 관리 작업
- **원클릭 저장소 설정**: 한 번의 클릭으로 DGit 저장소 초기화
- **비주얼 커밋 인터페이스**: 메시지 입력이 포함된 직관적인 커밋 다이얼로그
- **자동 스테이징**: 원활한 워크플로를 위한 커밋 전 자동 파일 스테이징
- **커밋 히스토리**: 프로젝트 진화 과정의 아름다운 타임라인 뷰

### 🔄 고급 복원 시스템
- **모달 버전 선택**: 복원 지점 선택을 위한 우아한 모달 인터페이스
- **버전 미리보기**: 복원 전 커밋 메시지, 날짜, 해시 확인
- **안전한 복원 프로세스**: 실수로 인한 데이터 손실 방지를 위한 확인 다이얼로그
- **스마트 파일 매칭**: 정확한 복원을 위한 지능적 파일 경로 해석

### 📊 프로젝트 관리
- **최근 프로젝트**: 최근에 열었던 프로젝트에 빠르게 접근
- **프로젝트 상태 카드**: 프로젝트 정보의 깔끔하고 체계적인 표시
- **실시간 업데이트**: 라이브 상태 업데이트 및 파일 스캔
- **터미널 출력**: 상세한 작업 피드백을 위한 통합 터미널

## 🛠️ 기술 스택

- **Electron**: 크로스 플랫폼 데스크탑 앱 프레임워크
- **Node.js**: 백엔드 작업 및 파일 시스템 접근
- **HTML/CSS/JavaScript**: 네이티브 스타일링을 적용한 모던 웹 기술
- **IPC Communication**: 안전한 메인-렌더러 프로세스 통신

## 📋 시스템 요구사항

- **macOS**: 10.14 이상 (macOS 최적화)
- **DGit CLI**: 설치되어 있고 접근 가능해야 함
- **Node.js**: 16.0 이상
- **Electron**: 28.0 이상

## 🚀 설치 방법

### 방법 1: 릴리즈 다운로드
1. [Releases](https://github.com/your-username/dgit-gui/releases)에서 최신 릴리즈 다운로드
2. `.dmg` 파일을 마운트하고 DGit GUI를 응용 프로그램으로 드래그
3. 응용 프로그램 폴더에서 실행

### 방법 2: 소스에서 빌드
```bash
# 저장소 클론
git clone https://github.com/your-username/dgit-gui.git
cd dgit-gui

# 의존성 설치
npm install

# 개발 서버 시작
npm start

# 프로덕션 빌드
npm run build
```

## 🎯 빠른 시작

1. **DGit GUI 실행** - 응용 프로그램에서 실행하거나 `npm start`
2. **프로젝트 선택** - "새 프로젝트 선택" 클릭 또는 ⌘+O 사용
3. **저장소 초기화** - 새 프로젝트의 경우 "저장소 초기화" 클릭
4. **파일 추가** - "모든 파일 추가" 사용 또는 ⌘+A로 파일 스테이징
5. **변경사항 커밋** - "커밋" 클릭 또는 ⌘+S로 설명과 함께 커밋
6. **파일 복원** - 파일 선택 후 "복원" 클릭하여 버전 선택

## ⌨️ 키보드 단축키

| 단축키 | 동작 |
|--------|------|
| `⌘+O` | 프로젝트 열기/선택 |
| `⌘+A` | 모든 파일 추가 |
| `⌘+S` | 변경사항 커밋 |
| `⌘+R` | 상태 새로고침 |
| `⌘+W` | 홈으로 돌아가기 |
| `Esc` | 모달 닫기/홈으로 |
| `Enter` | 모달에서 확인 |

## 🎨 UI Components

### Start Screen
- **Project Selection**: Native file picker integration
- **Recent Projects**: Quick access with project paths and names
- **Clean Welcome**: Intuitive first-time user experience

### Main Interface
- **Sidebar Navigation**: Project info and navigation sections
- **Content Views**: 
  - 📊 Project Status
  - 📁 Design Files
  - 📝 Commit History
  - ⚙️ Settings

### Modals & Dialogs
- **Commit Modal**: Rich text input with preview
- **Restore Modal**: Version selection with commit details
- **Confirmation Dialogs**: Safe operation confirmations

## 🔧 Configuration

### DGit Path Detection
The app automatically detects DGit installation in:
- Bundled binary (if packaged)
- `~/Desktop/DGIT/dgit/dgit`
- System PATH
- Common installation directories

### Recent Projects
Projects are automatically saved to `~/.dgit-gui/recent-projects.json`

## 🐛 Troubleshooting

### DGit Not Found
```bash
# Check DGit installation
which dgit
dgit --version

# Install DGit CLI first
# Follow instructions at: https://github.com/3pxTeam/DGIT-CLI
```

### Commit Failures
- Ensure files are modified before committing
- Check repository initialization with "저장소 초기화"
- Verify DGit CLI is working: `dgit status`

### Restore Issues
- Ensure at least one commit exists
- Check file selection before attempting restore
- Verify version numbers in commit history

## 🎯 Supported File Types

### Design Files
- **Adobe**: `.psd`, `.ai`
- **Sketch**: `.sketch`
- **Figma**: `.fig`
- **Adobe XD**: `.xd`

### Image Files
- **Raster**: `.png`, `.jpg`, `.jpeg`, `.gif`
- **Vector**: `.svg`

### Other Files
- All other file types with generic file icon

## 🚧 Development

### Project Structure
```
dgit-gui/
├── main.js          # Electron main process
├── preload.js       # IPC bridge
├── renderer/        # Frontend files
│   ├── index.html   # Main UI structure
│   ├── index.js     # Frontend logic
│   └── style.css    # macOS-style CSS
├── assets/          # Icons and images
└── package.json     # Dependencies and scripts
```

### Development Commands
```bash
npm start           # Start development
npm run dev         # Start with dev tools
npm run build       # Build for production
npm run pack        # Package for distribution
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **DGit CLI Team**: For the amazing underlying version control system
- **Electron Team**: For the cross-platform desktop framework
- **macOS Design**: For inspiration on native interface design

## 🔗 Related Links

- [DGit CLI Repository](https://github.com/3pxTeam/DGIT-CLI)
- [Electron Documentation](https://www.electronjs.org/docs)
- [macOS Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/macos/)

---

<p align="center">
  <strong>Built with ❤️ for designers and creative professionals</strong>
</p>
