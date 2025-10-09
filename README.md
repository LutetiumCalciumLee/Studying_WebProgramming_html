<details>
<summary>ENG (English Version)</summary>

# Chapter 1. Web Basics

**Key Points:**

- **Purpose and Structure of the Web**  
  The web was created to share and view documents across multiple computers. Web documents are specifically designed for the web, distinct from other electronic documents. The World Wide Web (WWW) is a network of information, interconnected like a spider’s web, using the internet as its foundation.
- **Web Components**  
  The web consists of web servers (which store and manage web content) and web clients (browsers that request and display content). Web servers respond to client requests by sending web documents, images, and other data. Web clients (browsers) provide the user interface and handle displaying the received content.
- **Internet vs. Web**  
  The internet is a broader network infrastructure established before the web, supporting various services like email, file transfer, and chat. The web is just one of many services running on the internet, focused on sharing hyperlinked documents.
- **Web Browsers**  
  Early browsers included WorldWideWeb (later Nexus), Netscape Navigator, Internet Explorer, Opera, Safari, Mozilla Firefox, Google Chrome, and Microsoft Edge. Each browser has unique features and market share has shifted over time, with Chrome being the most widely used as of recent years.
- **Building a Website**  
  Setting up a website involves installing web server software, storing web pages and media, and developing server applications as needed. Popular web server software includes Apache, IIS, nginx, and Google Web Server. Server applications can be built using languages like JavaScript, JSP, Java, C/C++, PHP, Perl, and Python.
- **Web Documents vs. Electronic Documents**  
  Electronic documents (like Word files) are stored as single files containing all content. Web documents are written in HTML, stored as separate files per page, and linked via hyperlinks. Web pages store only text; images and media are kept as separate files and referenced within the page.
- **URLs and HTTP**  
  A web page’s address (URL) includes the protocol, server address, port number, path, and file name. Communication between browsers and servers is managed by the HTTP protocol, which defines how requests and responses are handled.
- **The Birth and Success of the Web**  
  Tim Berners-Lee proposed the web in 1989 and developed the first web server and browser at CERN. The web succeeded due to the simplicity of HTML, efficient HTTP communication, and clear separation of server and client responsibilities.
- **Ubiquity of the Web**  
  The web is now a fundamental platform for information and device management, used in TVs, routers, and more. Web servers are often embedded in devices to provide easy configuration via browsers.
- **Web Page Structure: HTML, CSS, JavaScript**  
  HTML defines the structure and content. CSS styles the appearance. JavaScript handles behavior and interactivity. These components are developed separately for modularity and flexibility.
- **HTML5: Purpose and Features**  
  HTML5 was created to address compatibility issues and the growing diversity of internet devices. It aims to provide a universal standard that works across PCs, mobile devices, and more, eliminating the need for plugins like Flash or ActiveX. HTML5 supports advanced features like multimedia (audio, video), graphics (Canvas, SVG), offline applications, geolocation, and more, with standardized APIs.
- **Editing HTML5 Documents**  
  HTML5 files can be created with any text editor and should be saved in UTF-8 encoding. WYSIWYG editors (like Dreamweaver or Sublime Text) offer visual editing and error checking.
- **Debugging and Validation**  
  Browsers provide developer tools for debugging HTML, CSS, and JavaScript. Validation tools help ensure code adheres to standards.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 1장. 웹 기초

**핵심 내용:**

- **웹의 목적 및 구조**  
  웹은 여러 컴퓨터에 걸쳐 문서를 공유 및 열람하기 위해 만들어진 정보망임. 웹 문서는 타 전자문서와는 구별되는 웹 전용 문서로, 인터넷 기반의 거미줄 형태 네트워크로 정보를 연결함.
- **웹의 구성 요소**  
  웹은 콘텐츠를 저장·관리하는 웹 서버와 요청·표시를 담당하는 웹 클라이언트(브라우저)로 구성됨. 서버는 클라이언트의 요청에 따라 웹 문서, 이미지 등 데이터를 전달하며, 클라이언트는 사용자 인터페이스와 콘텐츠 표시 역할을 함.
- **인터넷과 웹의 차이**  
  인터넷은 웹보다 먼저 구축된 광범위한 네트워크 인프라임. 이메일, 파일전송, 채팅 등 다양한 서비스가 동작하며, 웹은 하이퍼링크 문서 공유에 특화된 인터넷 기반 서비스임.
- **웹 브라우저**  
  초기 브라우저에는 WorldWideWeb(이후 Nexus), 넷스케이프 네비게이터, 인터넷 익스플로러, 오페라, 사파리, 모질라 파이어폭스, 구글 크롬, 마이크로소프트 엣지 등이 있음. 각 브라우저는 고유 기능을 지니며, 최근에는 크롬이 가장 널리 사용되고 있음.
- **웹사이트 구축 절차**  
  웹 서버 소프트웨어 설치, 웹페이지·미디어 저장, 서버 앱 개발 등이 필요함. 대표적인 서버 소프트웨어로 아파치, IIS, nginx, Google Web Server 등이 사용됨. 서버 앱은 JavaScript, JSP, Java, C/C++, PHP, Perl, Python 등으로 구현 가능함.
- **웹 문서와 전자문서**  
  워드처럼 하나의 파일에 모든 내용을 담는 전자문서와 달리, 웹 문서는 HTML로 각 페이지가 별도 파일로 작성되고 하이퍼링크로 연결됨. 웹 페이지는 텍스트만 저장하며, 이미지·미디어는 별도 파일로 관리 후 참조함.
- **URL과 HTTP**  
  웹페이지의 주소(URL)는 프로토콜, 서버주소, 포트번호, 경로, 파일명 등으로 구성됨. 브라우저-서버 간 통신은 HTTP 프로토콜로 정의됨.
- **웹 탄생과 성공 요인**  
  1989년 팀 버너스리가 CERN에서 웹을 제안 후 첫 웹 서버와 브라우저 개발함. HTML의 단순함, HTTP의 효율, 서버·클라이언트 역할 분리가 웹 대중화에 크게 기여함.
- **웹의 범용성**  
  웹은 TV, 라우터 등 다양한 기기 관리 플랫폼으로도 사용됨. 웹 서버가 장비에 내장되어 브라우저 통해 설정할 수 있음.
- **웹문서 구조: HTML, CSS, JavaScript**  
  HTML은 구조·내용 정의, CSS는 스타일 지정, JavaScript는 동작·인터렉티브 기능 구현 역할 분담함. 이들 요소는 모듈화·유연성 확보를 위해 분리 개발됨.
- **HTML5: 목적과 특징**  
  HTML5는 호환성·기기 다변화 문제 해결을 위한 범용 표준 제공을 목표로 함. 모든 환경에서 플러그인 없이 동작하며, 멀티미디어, 그래픽, 오프라인 앱, 지오로케이션 등 고급 기능과 표준 API를 지원함.
- **HTML5 문서 작성**  
  모든 텍스트 에디터로 작성 가능하며 UTF-8로 저장 추천함. 드림위버나 서블라임 텍스트 같은 WYSIWYG 편집기는 시각적 편집과 오류 검사를 지원함.
- **디버깅 및 유효성 검사**  
  브라우저 개발자 도구가 HTML, CSS, JavaScript 디버깅을 지원하며, 유효성 검사 도구로 코드 표준 준수 확인 가능함.

</details>
