let currentQuestionIndex = 0; // 現在の問題番号 (0からスタート)
const totalQuestions = questions.length;

// DOM要素の取得
const questionNumberEl = document.getElementById('question-number');
const questionTextEl = document.getElementById('question-text');
const answerTextEl = document.getElementById('answer-text');
const answerBoxEl = document.getElementById('answer-box');
const answerToggleBtn = document.getElementById('answer-toggle');
const prevButton = document.getElementById('prev-button');
const nextButton = document.getElementById('next-button');
const quizArea = document.getElementById('quiz-area');
const resultArea = document.getElementById('result-area');
const restartButton = document.getElementById('restart-button');

/**
 * 現在の問題を表示する関数
 */
function displayQuestion() {
    if (currentQuestionIndex >= totalQuestions) {
        // 全問終了
        quizArea.classList.add('hidden');
        resultArea.classList.remove('hidden');
        return;
    }

    const currentQ = questions[currentQuestionIndex];

    // 質問と番号の更新
    questionNumberEl.textContent = `問題 ${currentQuestionIndex + 1} / ${totalQuestions}`;
    questionTextEl.textContent = currentQ.q;

    // 答えとボタンの状態リセット
    answerTextEl.textContent = currentQ.a;
    answerBoxEl.classList.add('hidden');
    answerToggleBtn.textContent = '答えを表示';

    // ボタンの有効/無効設定
    prevButton.disabled = currentQuestionIndex === 0;
    nextButton.disabled = false; // 次の問題がない場合は後続処理で制御
    
    if (currentQuestionIndex === totalQuestions - 1) {
        nextButton.textContent = '結果を見る';
    } else {
        nextButton.textContent = '次の問題';
    }
}

/**
 * 答え表示/非表示を切り替える関数
 */
function toggleAnswer() {
    const isHidden = answerBoxEl.classList.toggle('hidden');
    answerToggleBtn.textContent = isHidden ? '答えを表示' : '答えを隠す';
}

// --- イベントリスナー設定 ---

// 答え表示ボタン
answerToggleBtn.addEventListener('click', toggleAnswer);

// 次へボタン
nextButton.addEventListener('click', () => {
    currentQuestionIndex++;
    displayQuestion();
});

// 前へボタン
prevButton.addEventListener('click', () => {
    currentQuestionIndex--;
    displayQuestion();
});

// 再スタートボタン
restartButton.addEventListener('click', () => {
    currentQuestionIndex = 0;
    resultArea.classList.add('hidden');
    quizArea.classList.remove('hidden');
    nextButton.textContent = '次の問題'; // ボタンテキストをリセット
    displayQuestion();
});

// 初回表示
displayQuestion();
