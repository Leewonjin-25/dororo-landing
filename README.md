 도로로 (Dororo) - 도로 균열 보수 동아리

<div align="center">

<img src="https://img.shields.io/badge/도로로-Road%20Repair%20Club-C9A86A?style=for-the-badge" alt="도로로">
<br><br>

</div>

<!-- 스타일 정의 -->
<style>
    .dororo-container {
        font-family: 'Noto Sans KR', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }
    
    .hero-section {
        background: linear-gradient(135deg, #F5EFE7 0%, #F0E6D8 100%);
        padding: 60px 40px;
        border-radius: 20px;
        text-align: center;
        margin: 30px 0;
        box-shadow: 0 4px 20px rgba(62, 39, 35, 0.1);
    }
    
    .hero-badge {
        display: inline-block;
        background: rgba(201, 168, 106, 0.15);
        border: 2px solid rgba(201, 168, 106, 0.4);
        padding: 10px 25px;
        border-radius: 50px;
        font-size: 16px;
        font-weight: 600;
        color: #A67C52;
        margin-bottom: 20px;
    }
    
    .hero-title {
        font-size: 48px;
        font-weight: 800;
        color: #3E2723;
        margin: 20px 0;
        line-height: 1.2;
    }
    
    .gradient-text {
        background: linear-gradient(135deg, #C9A86A 0%, #A67C52 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }
    
    .hero-description {
        font-size: 18px;
        color: #6D4C41;
        line-height: 1.8;
        margin: 20px 0;
    }
    
    .stats-container {
        display: flex;
        justify-content: center;
        gap: 60px;
        margin: 40px 0;
        flex-wrap: wrap;
    }
    
    .stat-item {
        text-align: center;
    }
    
    .stat-number {
        font-size: 48px;
        font-weight: 800;
        background: linear-gradient(135deg, #C9A86A 0%, #A67C52 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }
    
    .stat-label {
        font-size: 16px;
        color: #6D4C41;
        margin-top: 5px;
    }
    
    .cards-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 30px;
        margin: 40px 0;
    }
    
    .info-card {
        background: white;
        border: 1px solid rgba(62, 39, 35, 0.1);
        border-radius: 20px;
        padding: 40px;
        transition: all 0.3s ease;
        box-shadow: 0 2px 10px rgba(62, 39, 35, 0.05);
    }
    
    .info-card:hover {
        transform: translateY(-8px);
        box-shadow: 0 8px 30px rgba(62, 39, 35, 0.15);
        border-color: rgba(201, 168, 106, 0.3);
    }
    
    .card-title {
        font-size: 24px;
        font-weight: 700;
        color: #3E2723;
        margin: 20px 0 15px 0;
    }
    
    .card-description {
        color: #6D4C41;
        line-height: 1.7;
        margin-bottom: 20px;
    }
    
    .card-features {
        list-style: none;
        padding: 0;
        margin: 20px 0;
    }
    
    .card-features li {
        padding: 10px 0;
        color: #6D4C41;
        display: flex;
        align-items: center;
        gap: 10px;
    }
    
    .card-features li:before {
        content: "✓";
        color: #C9A86A;
        font-weight: bold;
        font-size: 18px;
    }
    
    .card-duration {
        display: inline-block;
        background: rgba(201, 168, 106, 0.1);
        color: #A67C52;
        padding: 8px 20px;
        border-radius: 50px;
        font-weight: 600;
        font-size: 14px;
        margin-top: 20px;
    }
    
    .button-primary {
        display: inline-block;
        background: linear-gradient(135deg, #C9A86A 0%, #A67C52 100%);
        color: white;
        padding: 15px 40px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 600;
        font-size: 16px;
        box-shadow: 0 4px 15px rgba(201, 168, 106, 0.3);
        transition: all 0.3s ease;
        margin: 10px;
    }
    
    .button-primary:hover {
        transform: translateY(-3px);
        box-shadow: 0 6px 20px rgba(201, 168, 106, 0.4);
        color: white;
    }
    
    .button-secondary {
        display: inline-block;
        background: rgba(62, 39, 35, 0.08);
        color: #3E2723;
        padding: 15px 40px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 600;
        font-size: 16px;
        border: 1px solid rgba(62, 39, 35, 0.15);
        transition: all 0.3s ease;
        margin: 10px;
    }
    
    .button-secondary:hover {
        background: rgba(62, 39, 35, 0.12);
        transform: translateY(-3px);
        color: #3E2723;
    }
    
    .quiz-section {
        background: linear-gradient(180deg, #F5EFE7 0%, #F0E6D8 100%);
        padding: 60px 40px;
        border-radius: 20px;
        margin: 40px 0;
    }
    
    .section-title {
        font-size: 36px;
        font-weight: 800;
        color: #3E2723;
        text-align: center;
        margin-bottom: 15px;
    }
    
    .section-description {
        font-size: 18px;
        color: #6D4C41;
        text-align: center;
        margin-bottom: 40px;
    }
    
    .quiz-item {
        background: white;
        padding: 30px;
        border-radius: 15px;
        margin: 20px 0;
        border-left: 4px solid #C9A86A;
    }
    
    .quiz-question {
        font-size: 18px;
        font-weight: 600;
        color: #3E2723;
        margin-bottom: 15px;
    }
    
    .quiz-answer {
        color: #6D4C41;
        line-height: 1.7;
        padding: 15px;
        background: rgba(201, 168, 106, 0.05);
        border-radius: 10px;
        margin-top: 10px;
    }
    
    @media (max-width: 768px) {
        .hero-title {
            font-size: 32px;
        }
        
        .stats-container {
            gap: 30px;
        }
        
        .cards-grid {
            grid-template-columns: 1fr;
        }
    }
</style>

<div class="dororo-container">

<!-- 히어로 섹션 -->
<div class="hero-section">
    <div class="hero-badge">🛣️ 안전한 도로를 만드는 우리</div>
    <h1 class="hero-title">
        도로의 상처를<br>
        <span class="gradient-text">치유하는 기술</span>
    </h1>
    <p class="hero-description">
        도로 균열 보수의 모든 것을 배우고 실천하는 교육 동아리입니다.<br>
        이론부터 실습까지, 함께 배우며 더 안전한 도로 환경을 만들어갑니다.
    </p>
    
    <div style="margin: 30px 0;">
        <a href="https://courageous-halibut-239.notion.site/2eb771d6460080afb799fc699ef93977?pvs=105" class="button-primary" target="_blank">가입하기</a>
        <a href="#quiz" class="button-secondary">퀴즈 풀어보기</a>
    </div>
    
    <div class="stats-container">
        <div class="stat-item">
            <div class="stat-number">150+</div>
            <div class="stat-label">동아리 회원</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">50+</div>
            <div class="stat-label">보수 프로젝트</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">98%</div>
            <div class="stat-label">만족도</div>
        </div>
    </div>
</div>

<!-- 학습 목표 섹션 -->
<h2 class="section-title" style="margin-top: 60px;">무엇을 배우나요?</h2>
<p class="section-description">도로로에서는 체계적인 커리큘럼을 통해 도로 균열 보수의 전문가로 성장할 수 있습니다.</p>

<div class="cards-grid">
    <!-- 카드 1 -->
    <div class="info-card">
        <div style="font-size: 48px; margin-bottom: 10px;">🔍</div>
        <h3 class="card-title">균열 진단 기술</h3>
        <p class="card-description">
            다양한 도로 균열 유형을 정확히 식별하고 분석하는 방법을 학습합니다. 
            선형, 망상형, 블록형, 포트홀 등 각 균열의 특성과 원인을 이해합니다.
        </p>
        <ul class="card-features">
            <li>균열 유형 분류법</li>
            <li>심각도 평가 기준</li>
            <li>현장 조사 실습</li>
        </ul>
        <span class="card-duration">4주 과정</span>
    </div>
    
    <!-- 카드 2 -->
    <div class="info-card">
        <div style="font-size: 48px; margin-bottom: 10px;">🛠️</div>
        <h3 class="card-title">보수 재료 및 공법</h3>
        <p class="card-description">
            최신 보수 재료의 특성과 적용 방법을 익히고, 상황에 맞는 최적의 공법을 선택하는 능력을 기릅니다. 
            이론과 실습을 병행합니다.
        </p>
        <ul class="card-features">
            <li>아스팔트 보수 재료</li>
            <li>콘크리트 보수 기법</li>
            <li>실전 보수 프로젝트</li>
        </ul>
        <span class="card-duration">6주 과정</span>
    </div>
    
    <!-- 카드 3 -->
    <div class="info-card">
        <div style="font-size: 48px; margin-bottom: 10px;">🛡️</div>
        <h3 class="card-title">안전 관리 및 품질 관리</h3>
        <p class="card-description">
            작업 현장에서의 안전 수칙과 품질 관리 기준을 학습합니다. 
            사고 예방과 고품질 보수 작업을 위한 체계적인 관리 방법을 익힙니다.
        </p>
        <ul class="card-features">
            <li>작업 안전 수칙</li>
            <li>품질 검사 기준</li>
            <li>환경 보호 가이드</li>
        </ul>
        <span class="card-duration">3주 과정</span>
    </div>
</div>

<!-- 퀴즈 섹션 -->
<div class="quiz-section" id="quiz">
    <h2 class="section-title">📝 도로 균열 퀴즈</h2>
    <p class="section-description">배운 내용을 확인해보세요! 5개의 문제를 풀고 당신의 실력을 테스트하세요.</p>
    
    <div class="quiz-item">
        <div class="quiz-question">Q1. 도로 균열 중 '선형 균열'의 주요 특징은 무엇인가요?</div>
        <details>
            <summary style="cursor: pointer; color: #C9A86A; font-weight: 600; padding: 10px 0;">정답 보기 ▼</summary>
            <div class="quiz-answer">
                <strong>정답:</strong> 일직선 또는 약간 구부러진 형태의 균열<br><br>
                <strong>해설:</strong> 선형 균열은 일직선 또는 약간 구부러진 형태로 나타나며, 주로 시공 이음부나 하부 구조물의 불균등 침하로 발생합니다.
            </div>
        </details>
    </div>
    
    <div class="quiz-item">
        <div class="quiz-question">Q2. 포트홀(Pothole)이 발생하는 주요 원인은 무엇인가요?</div>
        <details>
            <summary style="cursor: pointer; color: #C9A86A; font-weight: 600; padding: 10px 0;">정답 보기 ▼</summary>
            <div class="quiz-answer">
                <strong>정답:</strong> 수분 침투와 동결-융해 반복<br><br>
                <strong>해설:</strong> 포트홀은 균열 부위로 수분이 침투하고 동결-융해가 반복되면서 아스팔트가 떨어져 나가 발생합니다.
            </div>
        </details>
    </div>
    
    <div class="quiz-item">
        <div class="quiz-question">Q3. 도로 균열의 심각도를 평가할 때 고려해야 할 주요 요소가 아닌 것은?</div>
        <details>
            <summary style="cursor: pointer; color: #C9A86A; font-weight: 600; padding: 10px 0;">정답 보기 ▼</summary>
            <div class="quiz-answer">
                <strong>정답:</strong> 도로의 색상<br><br>
                <strong>해설:</strong> 균열의 심각도는 폭, 길이, 깊이, 위치 등으로 평가하며, 도로의 색상은 심각도 평가 요소가 아닙니다.
            </div>
        </details>
    </div>
    
    <div class="quiz-item">
        <div class="quiz-question">Q4. 망상형 균열(Alligator Cracking)이 주로 발생하는 위치는?</div>
        <details>
            <summary style="cursor: pointer; color: #C9A86A; font-weight: 600; padding: 10px 0;">정답 보기 ▼</summary>
            <div class="quiz-answer">
                <strong>정답:</strong> 교통량이 많은 차선<br><br>
                <strong>해설:</strong> 망상형 균열은 반복적인 교통하중으로 인해 주로 교통량이 많은 차선에서 발생하며, 악어 등처럼 보여 'Alligator Cracking'이라 불립니다.
            </div>
        </details>
    </div>
    
    <div class="quiz-item">
        <div class="quiz-question">Q5. 도로 균열 보수 시 가장 먼저 해야 할 작업은?</div>
        <details>
            <summary style="cursor: pointer; color: #C9A86A; font-weight: 600; padding: 10px 0;">정답 보기 ▼</summary>
            <div class="quiz-answer">
                <strong>정답:</strong> 균열 부위 청소 및 이물질 제거<br><br>
                <strong>해설:</strong> 효과적인 보수를 위해서는 먼저 균열 부위의 먼지, 이물질, 느슨한 재료를 제거하여 보수 재료가 잘 접착될 수 있도록 해야 합니다.
            </div>
        </details>
    </div>
</div>

</div>

---

## � 기술 스택

- **HTML5** - 시맨틱 마크업
- **CSS3** - 모던 스타일링
- **JavaScript** - 인터랙티브 기능
- **Fonts** - Noto Sans KR, Outfit

## � 프로젝트 파일

- `index.html` - 메인 랜딩 페이지
- `style.css` - 베이지 테마 스타일
- `script.js` - 인터랙션 로직
- `quiz.js` - 퀴즈 시스템

## 🚀 GitHub Pages로 보기

완전한 인터랙티브 버전을 보려면 GitHub Pages를 사용하세요:

```bash
# 저장소 업로드 후
# Settings → Pages → Source: main branch
# https://YOUR-USERNAME.github.io/dororo-landing/
```

---

<div align="center">

**🛣️ 도로로와 함께 더 안전한 도로를 만들어가요! ✨**

Made with ❤️ by Dororo Team

</div>
