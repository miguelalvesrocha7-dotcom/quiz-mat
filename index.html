<!doctype html>
<html lang="pt-BR" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quiz STEAM</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet">
  <style>
    * {
      font-family: 'Plus Jakarta Sans', sans-serif;
    }
    
    .gradient-bg {
      background: linear-gradient(135deg, #EFF6FF 0%, #DBEAFE 50%, #BFDBFE 100%);
    }
    
    .card-hover {
      transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
    
    .card-hover:hover {
      transform: translateY(-4px);
      box-shadow: 0 20px 40px -12px rgba(37, 99, 235, 0.25);
    }
    
    .btn-primary {
      background: linear-gradient(135deg, #2563EB 0%, #1D4ED8 100%);
      transition: all 0.3s ease;
    }
    
    .btn-primary:hover {
      background: linear-gradient(135deg, #1D4ED8 0%, #1E40AF 100%);
      transform: translateY(-2px);
      box-shadow: 0 10px 20px -5px rgba(37, 99, 235, 0.4);
    }
    
    .option-btn {
      transition: all 0.2s ease;
    }
    
    .option-btn:hover:not(.selected):not(.correct):not(.incorrect) {
      border-color: #2563EB;
      background: #EFF6FF;
    }
    
    .option-btn.selected {
      border-color: #2563EB;
      background: #DBEAFE;
    }
    
    .option-btn.correct {
      border-color: #16A34A;
      background: #DCFCE7;
    }
    
    .option-btn.incorrect {
      border-color: #DC2626;
      background: #FEE2E2;
    }
    
    .fade-in {
      animation: fadeIn 0.4s ease-out;
    }
    
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(10px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    .slide-up {
      animation: slideUp 0.5s ease-out;
    }
    
    @keyframes slideUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    .pulse-ring {
      animation: pulseRing 2s ease-out infinite;
    }
    
    @keyframes pulseRing {
      0% {
        transform: scale(0.8);
        opacity: 1;
      }
      100% {
        transform: scale(1.4);
        opacity: 0;
      }
    }
    
    .progress-bar {
      transition: width 0.5s ease-out;
    }
    
    .blob {
      position: absolute;
      border-radius: 50%;
      filter: blur(60px);
      opacity: 0.4;
      z-index: 0;
    }
  </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full gradient-bg overflow-auto">
  <div id="app" class="min-h-full w-full relative"><!-- Decorative blobs -->
   <div class="blob bg-blue-300 w-64 h-64 top-0 left-0 -translate-x-1/2 -translate-y-1/2" style="position: fixed;"></div>
   <div class="blob bg-blue-400 w-48 h-48 bottom-0 right-0 translate-x-1/4 translate-y-1/4" style="position: fixed;"></div><!-- Home Page -->
   <div id="home-page" class="relative z-10 px-4 py-8 md:py-12">
    <div class="max-w-4xl mx-auto"><!-- Header -->
     <header class="text-center mb-10 slide-up">
      <div class="inline-flex items-center justify-center w-20 h-20 bg-white rounded-2xl shadow-lg mb-6"><i data-lucide="brain" class="w-10 h-10 text-blue-600"></i>
      </div>
      <h1 id="site-title" class="text-4xl md:text-5xl font-extrabold text-gray-800 mb-4">Quiz STEAM</h1>
      <p id="site-description" class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto leading-relaxed">Teste seus conhecimentos sobre sustentabilidade e soluções criativas para problemas do dia a dia na escola!</p>
     </header><!-- Topics Section -->
     <section class="mb-10">
      <h2 class="text-2xl font-bold text-gray-800 mb-6 text-center"><i data-lucide="layers" class="inline w-6 h-6 mr-2 text-blue-600"></i> Escolha um Tópico</h2>
      <div id="topics-grid" class="grid grid-cols-1 md:grid-cols-3 gap-6"><!-- Topic cards will be rendered here -->
      </div>
     </section><!-- Start Button -->
     <div class="text-center"><button id="start-random-btn" class="btn-primary text-white font-semibold px-8 py-4 rounded-xl text-lg shadow-lg inline-flex items-center gap-3"> <i data-lucide="shuffle" class="w-5 h-5"></i> <span id="start-button-text">Quiz Aleatório</span> </button>
      <p class="text-gray-500 mt-3 text-sm">Ou clique em um tópico acima</p>
     </div>
    </div>
   </div><!-- Quiz Page -->
   <div id="quiz-page" class="relative z-10 px-4 py-8 hidden">
    <div class="max-w-2xl mx-auto"><!-- Quiz Header -->
     <div class="bg-white rounded-2xl shadow-lg p-6 mb-6">
      <div class="flex items-center justify-between mb-4"><button id="back-btn" class="flex items-center gap-2 text-gray-600 hover:text-blue-600 transition-colors"> <i data-lucide="arrow-left" class="w-5 h-5"></i> <span class="font-medium">Voltar</span> </button>
       <div class="flex items-center gap-2 text-gray-600"><i data-lucide="help-circle" class="w-5 h-5"></i> <span id="question-counter" class="font-semibold">1/5</span>
       </div>
      </div><!-- Progress Bar -->
      <div class="h-3 bg-gray-100 rounded-full overflow-hidden">
       <div id="progress-bar" class="progress-bar h-full bg-gradient-to-r from-blue-500 to-blue-600 rounded-full" style="width: 0%"></div>
      </div>
     </div><!-- Question Card -->
     <div id="question-card" class="bg-white rounded-2xl shadow-lg p-6 md:p-8 fade-in">
      <div class="flex items-start gap-4 mb-6">
       <div class="flex-shrink-0 w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center"><i data-lucide="lightbulb" class="w-6 h-6 text-blue-600"></i>
       </div>
       <div><span id="topic-badge" class="inline-block px-3 py-1 bg-blue-100 text-blue-700 text-sm font-medium rounded-full mb-2"> Tópico </span>
        <h3 id="question-text" class="text-xl md:text-2xl font-bold text-gray-800 leading-relaxed">Pergunta aqui</h3>
       </div>
      </div><!-- Options -->
      <div id="options-container" class="space-y-3"><!-- Options will be rendered here -->
      </div><!-- Feedback -->
      <div id="feedback-container" class="hidden mt-6 p-4 rounded-xl">
       <div class="flex items-center gap-3">
        <div id="feedback-icon" class="w-10 h-10 rounded-full flex items-center justify-center"><i data-lucide="check" class="w-5 h-5"></i>
        </div>
        <p id="feedback-text" class="font-medium"></p>
       </div>
      </div><!-- Next Button --> <button id="next-btn" class="hidden w-full btn-primary text-white font-semibold py-4 rounded-xl mt-6 flex items-center justify-center gap-2"> <span>Próxima Pergunta</span> <i data-lucide="arrow-right" class="w-5 h-5"></i> </button>
     </div><!-- Score Display -->
     <div class="mt-6 bg-white rounded-2xl shadow-lg p-4 flex items-center justify-center gap-6">
      <div class="flex items-center gap-2"><i data-lucide="trophy" class="w-5 h-5 text-yellow-500"></i> <span class="font-semibold text-gray-700">Pontos: <span id="current-score">0</span></span>
      </div>
      <div class="w-px h-6 bg-gray-200"></div>
      <div class="flex items-center gap-2"><i data-lucide="check-circle" class="w-5 h-5 text-green-500"></i> <span class="font-semibold text-gray-700">Acertos: <span id="correct-count">0</span></span>
      </div>
     </div>
    </div>
   </div><!-- Results Page -->
   <div id="results-page" class="relative z-10 px-4 py-8 hidden">
    <div class="max-w-lg mx-auto">
     <div class="bg-white rounded-2xl shadow-lg p-8 text-center slide-up"><!-- Result Icon -->
      <div id="result-icon-container" class="relative inline-flex items-center justify-center mb-6">
       <div class="absolute w-24 h-24 bg-blue-200 rounded-full pulse-ring"></div>
       <div id="result-icon" class="relative w-24 h-24 bg-gradient-to-br from-blue-500 to-blue-600 rounded-full flex items-center justify-center"><i data-lucide="trophy" class="w-12 h-12 text-white"></i>
       </div>
      </div><!-- Result Title -->
      <h2 id="result-title" class="text-3xl font-extrabold text-gray-800 mb-2">Parabéns!</h2>
      <p id="result-message" class="text-gray-600 mb-8">Você completou o quiz!</p><!-- Score Card -->
      <div class="bg-gradient-to-br from-blue-50 to-blue-100 rounded-2xl p-6 mb-8">
       <div class="grid grid-cols-2 gap-4">
        <div class="bg-white rounded-xl p-4 shadow-sm">
         <div class="text-3xl font-extrabold text-blue-600" id="final-score">
          0
         </div>
         <div class="text-gray-500 text-sm font-medium">
          Pontos
         </div>
        </div>
        <div class="bg-white rounded-xl p-4 shadow-sm">
         <div class="text-3xl font-extrabold text-green-600" id="final-correct">
          0/5
         </div>
         <div class="text-gray-500 text-sm font-medium">
          Acertos
         </div>
        </div>
       </div>
       <div class="mt-4 bg-white rounded-xl p-4 shadow-sm">
        <div class="text-2xl font-extrabold text-purple-600" id="final-percentage">
         0%
        </div>
        <div class="text-gray-500 text-sm font-medium">
         Aproveitamento
        </div>
       </div>
      </div><!-- Action Buttons -->
      <div class="space-y-3"><button id="retry-btn" class="w-full btn-primary text-white font-semibold py-4 rounded-xl flex items-center justify-center gap-2"> <i data-lucide="rotate-ccw" class="w-5 h-5"></i> <span>Refazer Quiz</span> </button> <button id="home-btn" class="w-full bg-gray-100 hover:bg-gray-200 text-gray-700 font-semibold py-4 rounded-xl flex items-center justify-center gap-2 transition-colors"> <i data-lucide="home" class="w-5 h-5"></i> <span>Voltar aos Tópicos</span> </button>
      </div>
     </div>
    </div>
   </div>
  </div>
  <script>
    // Quiz Data
    const quizTopics = [
      {
        id: 'lixo',
        title: 'Lixo na Sala de Aula',
        icon: 'trash-2',
        color: 'from-green-500 to-emerald-600',
        description: 'Sustentabilidade e gestão de resíduos',
        questions: [
          {
            text: 'Qual é o principal impacto ambiental do lixo jogado incorretamente na sala de aula?',
            options: [
              'Apenas deixa o ambiente feio',
              'Pode contaminar o solo e atrair pragas',
              'Não tem nenhum impacto',
              'Ajuda na decoração'
            ],
            correct: 1,
            explanation: 'O lixo incorretamente descartado pode contaminar o ambiente e atrair pragas!'
          },
          {
            text: 'Qual tecnologia poderia ajudar a conscientizar os alunos sobre o descarte correto?',
            options: [
              'Usar apenas cartazes de papel',
              'Ignorar o problema',
              'QR Codes com informações educativas ou avisos no celular',
              'Remover todas as lixeiras'
            ],
            correct: 2,
            explanation: 'Tecnologias como QR Codes podem trazer informações interativas!'
          },
          {
            text: 'Do ponto de vista da Engenharia, o que poderia melhorar a situação?',
            options: [
              'Mudar a localização e formato das lixeiras',
              'Pintar as paredes de outra cor',
              'Trocar as carteiras',
              'Aumentar o intervalo'
            ],
            correct: 0,
            explanation: 'A Engenharia pode ajudar redesenhando a posição e formato das lixeiras!'
          },
          {
            text: 'Como a Arte pode contribuir para reduzir o lixo na sala?',
            options: [
              'Criando mais lixo artístico',
              'Fazendo esculturas com lixo apenas',
              'Campanhas visuais criativas e educativas',
              'Pintando o chão'
            ],
            correct: 2,
            explanation: 'Campanhas visuais criativas podem conscientizar de forma efetiva!'
          },
          {
            text: 'Por que é importante calcular matematicamente quanto lixo é produzido por dia?',
            options: [
              'Não é importante',
              'Apenas para fazer conta',
              'Para dimensionar o problema e propor soluções adequadas',
              'Para competir com outras salas'
            ],
            correct: 2,
            explanation: 'Quantificar o problema ajuda a criar soluções proporcionais!'
          }
        ]
      },
      {
        id: 'energia',
        title: 'Gasto de Energia',
        icon: 'zap',
        color: 'from-yellow-500 to-orange-600',
        description: 'Economia e sustentabilidade energética',
        questions: [
          {
            text: 'Qual é a consequência ambiental de deixar luzes e ventiladores ligados desnecessariamente?',
            options: [
              'Nenhuma, a energia é infinita',
              'Maior consumo de recursos naturais e emissão de CO2',
              'Apenas gasta mais dinheiro',
              'Melhora a iluminação da escola'
            ],
            correct: 1,
            explanation: 'O desperdício de energia contribui para problemas ambientais!'
          },
          {
            text: 'Qual solução tecnológica poderia ajudar a reduzir o consumo?',
            options: [
              'Remover todos os equipamentos',
              'Sensores de presença e aplicativos de monitoramento',
              'Usar velas',
              'Deixar as janelas sempre abertas'
            ],
            correct: 1,
            explanation: 'Sensores e apps ajudam a automatizar o controle de energia!'
          },
          {
            text: 'Como a Engenharia pode organizar melhor o uso dos equipamentos?',
            options: [
              'Quebrando os equipamentos',
              'Criando sistemas de turnos e horários de uso',
              'Comprando mais equipamentos',
              'Ignorando o problema'
            ],
            correct: 1,
            explanation: 'Sistemas organizados de uso otimizam o consumo!'
          },
          {
            text: 'Que tipo de criação artística pode ajudar na conscientização?',
            options: [
              'Placas criativas com slogans sobre economia de energia',
              'Pinturas abstratas sem mensagem',
              'Músicas sobre outros temas',
              'Teatro sobre história antiga'
            ],
            correct: 0,
            explanation: 'Placas e slogans criativos chamam atenção para o problema!'
          },
          {
            text: 'Por que calcular a economia mensal de energia é importante?',
            options: [
              'Para mostrar os benefícios concretos das ações',
              'Só para fazer lição de matemática',
              'Não é importante',
              'Para gastar mais'
            ],
            correct: 0,
            explanation: 'Números concretos motivam e comprovam a efetividade das ações!'
          }
        ]
      },
      {
        id: 'celular',
        title: 'Uso do Celular',
        icon: 'smartphone',
        color: 'from-purple-500 to-indigo-600',
        description: 'Tecnologia e produtividade em sala',
        questions: [
          {
            text: 'De acordo com a Ciência, como o uso excessivo do celular afeta a aprendizagem?',
            options: [
              'Melhora a concentração',
              'Não tem efeito nenhum',
              'Prejudica a atenção e a retenção de informações',
              'Acelera o aprendizado'
            ],
            correct: 2,
            explanation: 'Estudos mostram que distrações digitais prejudicam a aprendizagem!'
          },
          {
            text: 'Qual aplicativo poderia transformar o celular em ferramenta educativa?',
            options: [
              'Apenas jogos de entretenimento',
              'Aplicativos educativos e cronômetros de foco',
              'Redes sociais sem moderação',
              'Aplicativos de compras'
            ],
            correct: 1,
            explanation: 'Apps educativos e de foco podem transformar o celular em aliado!'
          },
          {
            text: 'Que tipo de sistema a Engenharia poderia criar para melhor uso do celular?',
            options: [
              'Proibir totalmente os celulares',
              'Regras claras e sistemas de uso moderado',
              'Deixar livre sem regras',
              'Confiscar permanentemente'
            ],
            correct: 1,
            explanation: 'Sistemas com regras claras equilibram uso e aprendizado!'
          },
          {
            text: 'Como a Arte pode ajudar a criar combinados sobre o uso do celular?',
            options: [
              'Criando símbolos e combinados visuais claros',
              'Ignorando o problema',
              'Fazendo cartazes confusos',
              'Usando apenas texto longo'
            ],
            correct: 0,
            explanation: 'Símbolos visuais comunicam regras de forma efetiva!'
          },
          {
            text: 'Como a Matemática pode ajudar na gestão do tempo de uso do celular?',
            options: [
              'Não pode ajudar',
              'Calculando equações complexas',
              'Dividindo o tempo entre estudo e uso do celular',
              'Contando quantos celulares existem'
            ],
            correct: 2,
            explanation: 'A divisão equilibrada do tempo otimiza o uso do celular!'
          }
        ]
      }
    ];

    // Default configuration
    const defaultConfig = {
      site_title: 'Quiz STEAM',
      site_description: 'Teste seus conhecimentos sobre sustentabilidade e soluções criativas para problemas do dia a dia na escola!',
      start_button_text: 'Quiz Aleatório',
      primary_color: '#2563EB',
      secondary_color: '#1D4ED8',
      background_color: '#EFF6FF',
      text_color: '#1F2937',
      accent_color: '#3B82F6'
    };

    // App State
    let state = {
      currentPage: 'home',
      currentTopic: null,
      currentQuestionIndex: 0,
      score: 0,
      correctAnswers: 0,
      selectedAnswer: null,
      answered: false,
      questions: []
    };

    // Initialize Element SDK
    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange: async (config) => {
          document.getElementById('site-title').textContent = config.site_title || defaultConfig.site_title;
          document.getElementById('site-description').textContent = config.site_description || defaultConfig.site_description;
          document.getElementById('start-button-text').textContent = config.start_button_text || defaultConfig.start_button_text;
        },
        mapToCapabilities: (config) => ({
          recolorables: [
            {
              get: () => config.background_color || defaultConfig.background_color,
              set: (value) => window.elementSdk.setConfig({ background_color: value })
            },
            {
              get: () => config.primary_color || defaultConfig.primary_color,
              set: (value) => window.elementSdk.setConfig({ primary_color: value })
            },
            {
              get: () => config.text_color || defaultConfig.text_color,
              set: (value) => window.elementSdk.setConfig({ text_color: value })
            }
          ],
          borderables: [],
          fontEditable: undefined,
          fontSizeable: undefined
        }),
        mapToEditPanelValues: (config) => new Map([
          ['site_title', config.site_title || defaultConfig.site_title],
          ['site_description', config.site_description || defaultConfig.site_description],
          ['start_button_text', config.start_button_text || defaultConfig.start_button_text]
        ])
      });
    }

    // Render topic cards
    function renderTopics() {
      const grid = document.getElementById('topics-grid');
      grid.innerHTML = quizTopics.map((topic, index) => `
        <button onclick="startQuiz('${topic.id}')" class="card-hover bg-white rounded-2xl p-6 text-left shadow-lg border-2 border-transparent hover:border-blue-300" style="animation-delay: ${index * 100}ms">
          <div class="w-14 h-14 bg-gradient-to-br ${topic.color} rounded-xl flex items-center justify-center mb-4 shadow-lg">
            <i data-lucide="${topic.icon}" class="w-7 h-7 text-white"></i>
          </div>
          <h3 class="text-lg font-bold text-gray-800 mb-2">${topic.title}</h3>
          <p class="text-gray-500 text-sm">${topic.description}</p>
          <div class="mt-4 flex items-center text-blue-600 font-medium text-sm">
            <span>5 perguntas</span>
            <i data-lucide="chevron-right" class="w-4 h-4 ml-1"></i>
          </div>
        </button>
      `).join('');
      lucide.createIcons();
    }

    // Start quiz
    function startQuiz(topicId) {
      if (topicId === 'random') {
        const randomTopic = quizTopics[Math.floor(Math.random() * quizTopics.length)];
        state.currentTopic = randomTopic;
      } else {
        state.currentTopic = quizTopics.find(t => t.id === topicId);
      }
      
      state.questions = [...state.currentTopic.questions];
      state.currentQuestionIndex = 0;
      state.score = 0;
      state.correctAnswers = 0;
      state.selectedAnswer = null;
      state.answered = false;
      
      showPage('quiz');
      renderQuestion();
    }

    // Render current question
    function renderQuestion() {
      const question = state.questions[state.currentQuestionIndex];
      const totalQuestions = state.questions.length;
      
      document.getElementById('question-counter').textContent = `${state.currentQuestionIndex + 1}/${totalQuestions}`;
      document.getElementById('progress-bar').style.width = `${((state.currentQuestionIndex) / totalQuestions) * 100}%`;
      document.getElementById('topic-badge').textContent = state.currentTopic.title;
      document.getElementById('question-text').textContent = question.text;
      document.getElementById('current-score').textContent = state.score;
      document.getElementById('correct-count').textContent = state.correctAnswers;
      
      const optionsContainer = document.getElementById('options-container');
      optionsContainer.innerHTML = question.options.map((option, index) => `
        <button onclick="selectAnswer(${index})" class="option-btn w-full p-4 text-left rounded-xl border-2 border-gray-200 hover:border-blue-400 transition-all flex items-center gap-3" data-index="${index}">
          <span class="flex-shrink-0 w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center font-semibold text-gray-600">
            ${String.fromCharCode(65 + index)}
          </span>
          <span class="text-gray-700 font-medium">${option}</span>
        </button>
      `).join('');
      
      document.getElementById('feedback-container').classList.add('hidden');
      document.getElementById('next-btn').classList.add('hidden');
      
      const questionCard = document.getElementById('question-card');
      questionCard.classList.remove('fade-in');
      void questionCard.offsetWidth;
      questionCard.classList.add('fade-in');
      
      lucide.createIcons();
    }

    // Select answer
    function selectAnswer(index) {
      if (state.answered) return;
      
      state.selectedAnswer = index;
      state.answered = true;
      
      const question = state.questions[state.currentQuestionIndex];
      const isCorrect = index === question.correct;
      
      if (isCorrect) {
        state.score += 20;
        state.correctAnswers++;
      }
      
      // Update UI
      const options = document.querySelectorAll('.option-btn');
      options.forEach((btn, i) => {
        btn.classList.remove('selected');
        if (i === question.correct) {
          btn.classList.add('correct');
        } else if (i === index && !isCorrect) {
          btn.classList.add('incorrect');
        }
      });
      
      // Show feedback
      const feedbackContainer = document.getElementById('feedback-container');
      const feedbackIcon = document.getElementById('feedback-icon');
      const feedbackText = document.getElementById('feedback-text');
      
      feedbackContainer.classList.remove('hidden');
      
      if (isCorrect) {
        feedbackContainer.className = 'mt-6 p-4 rounded-xl bg-green-50 border border-green-200';
        feedbackIcon.className = 'w-10 h-10 rounded-full flex items-center justify-center bg-green-500';
        feedbackIcon.innerHTML = '<i data-lucide="check" class="w-5 h-5 text-white"></i>';
        feedbackText.className = 'font-medium text-green-700';
        feedbackText.textContent = '✨ Correto! ' + question.explanation;
      } else {
        feedbackContainer.className = 'mt-6 p-4 rounded-xl bg-red-50 border border-red-200';
        feedbackIcon.className = 'w-10 h-10 rounded-full flex items-center justify-center bg-red-500';
        feedbackIcon.innerHTML = '<i data-lucide="x" class="w-5 h-5 text-white"></i>';
        feedbackText.className = 'font-medium text-red-700';
        feedbackText.textContent = '❌ Ops! ' + question.explanation;
      }
      
      lucide.createIcons();
      
      // Update score display
      document.getElementById('current-score').textContent = state.score;
      document.getElementById('correct-count').textContent = state.correctAnswers;
      
      // Show next button
      const nextBtn = document.getElementById('next-btn');
      nextBtn.classList.remove('hidden');
      
      if (state.currentQuestionIndex === state.questions.length - 1) {
        nextBtn.innerHTML = '<span>Ver Resultado</span><i data-lucide="trophy" class="w-5 h-5"></i>';
      } else {
        nextBtn.innerHTML = '<span>Próxima Pergunta</span><i data-lucide="arrow-right" class="w-5 h-5"></i>';
      }
      
      lucide.createIcons();
    }

    // Next question
    function nextQuestion() {
      if (state.currentQuestionIndex < state.questions.length - 1) {
        state.currentQuestionIndex++;
        state.selectedAnswer = null;
        state.answered = false;
        renderQuestion();
      } else {
        showResults();
      }
    }

    // Show results
    function showResults() {
      const totalQuestions = state.questions.length;
      const percentage = Math.round((state.correctAnswers / totalQuestions) * 100);
      
      document.getElementById('final-score').textContent = state.score;
      document.getElementById('final-correct').textContent = `${state.correctAnswers}/${totalQuestions}`;
      document.getElementById('final-percentage').textContent = `${percentage}%`;
      
      const resultTitle = document.getElementById('result-title');
      const resultMessage = document.getElementById('result-message');
      const resultIcon = document.getElementById('result-icon');
      
      if (percentage >= 80) {
        resultTitle.textContent = '🏆 Excelente!';
        resultMessage.textContent = 'Você é um verdadeiro expert em STEAM! Continue assim!';
        resultIcon.className = 'relative w-24 h-24 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center';
      } else if (percentage >= 60) {
        resultTitle.textContent = '👏 Muito Bem!';
        resultMessage.textContent = 'Ótimo desempenho! Você está no caminho certo!';
        resultIcon.className = 'relative w-24 h-24 bg-gradient-to-br from-green-400 to-green-600 rounded-full flex items-center justify-center';
      } else if (percentage >= 40) {
        resultTitle.textContent = '💪 Bom Trabalho!';
        resultMessage.textContent = 'Continue estudando para melhorar ainda mais!';
        resultIcon.className = 'relative w-24 h-24 bg-gradient-to-br from-blue-400 to-blue-600 rounded-full flex items-center justify-center';
      } else {
        resultTitle.textContent = '📚 Continue Tentando!';
        resultMessage.textContent = 'Não desista! Cada erro é uma oportunidade de aprender!';
        resultIcon.className = 'relative w-24 h-24 bg-gradient-to-br from-purple-400 to-purple-600 rounded-full flex items-center justify-center';
      }
      
      showPage('results');
    }

    // Show page
    function showPage(page) {
      document.getElementById('home-page').classList.add('hidden');
      document.getElementById('quiz-page').classList.add('hidden');
      document.getElementById('results-page').classList.add('hidden');
      
      document.getElementById(`${page}-page`).classList.remove('hidden');
      state.currentPage = page;
    }

    // Event listeners
    document.getElementById('start-random-btn').addEventListener('click', () => startQuiz('random'));
    document.getElementById('back-btn').addEventListener('click', () => showPage('home'));
    document.getElementById('next-btn').addEventListener('click', nextQuestion);
    document.getElementById('retry-btn').addEventListener('click', () => startQuiz(state.currentTopic.id));
    document.getElementById('home-btn').addEventListener('click', () => showPage('home'));

    // Initialize
    renderTopics();
    lucide.createIcons();
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9d836482172ffa0a',t:'MTc3MjgyMTQxNy4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
