<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>PoKreGaM</title>
<style>
  body { font-family: Arial, sans-serif; margin:0; background:#f0f0f0; }
  header { background:#222; color:white; padding:10px 20px; display:flex; justify-content: space-between; align-items:center; }
  #languageSelector { margin-right: 20px; }
  nav button { background:none; border:none; color:white; margin: 0 5px; cursor:pointer; font-weight:bold; }
  nav button:hover { text-decoration: underline; }
  #authButtons button { margin-left: 10px; padding:5px 10px; background:#007bff; border:none; border-radius:5px; color:#fff; cursor:pointer; }
  #authButtons button:hover { background:#0056b3; }
  main { padding: 20px; max-width: 1100px; margin: auto; background: white; min-height: 80vh; box-sizing: border-box;}
  .hidden { display:none; }
  /* Avatars */
  .avatars { display: flex; flex-wrap: wrap; gap:10px; margin-bottom: 15px; }
  .avatar { border: 2px solid transparent; cursor: pointer; padding:5px; text-align:center; width: 100px; user-select:none;}
  .avatar.selected { border-color: #007bff; background:#e0f0ff; }
  .avatar img { width: 80px; height: 80px; object-fit: contain; }
  /* Forms */
  form input, form select, form textarea { padding: 6px; margin: 5px 0; width: 100%; box-sizing: border-box; }
  form label { font-weight: bold; }
  form .form-group { margin-bottom: 10px; }
  /* Profile */
  #profileHeader { display: flex; align-items: center; gap: 20px; margin-bottom: 20px; flex-wrap: wrap; }
  #profileAvatar img { width: 120px; height: 120px; border-radius: 10px; }
  #profileInfo { flex-grow: 1; min-width: 200px; }
  #profileInfo h2 { margin: 0; }
  #profileStats { display: flex; gap: 15px; margin-top: 10px; flex-wrap: wrap; }
  #profileStats div { background: #eee; padding: 8px 12px; border-radius: 6px; min-width: 80px; text-align: center; user-select:none;}
  /* Tabs */
  #tabs { margin-bottom: 20px; display:flex; flex-wrap: wrap; gap: 5px; }
  #tabs button { padding: 8px 16px; border: 1px solid #007bff; background: white; color: #007bff; cursor: pointer; border-radius: 5px; user-select:none; }
  #tabs button.active, #tabs button:hover { background: #007bff; color: white; }
  section.tabContent { display: none; }
  section.tabContent.active { display: block; }
  /* Ranking Table */
  table { width: 100%; border-collapse: collapse; margin-top: 10px; }
  table, th, td { border: 1px solid #ccc; }
  th, td { padding: 8px; text-align: center; }
  /* Friends */
  #friendsList div { background: #eee; margin: 5px 0; padding: 6px 10px; border-radius: 5px; user-select:none;}
  #activeFriends { font-style: italic; margin-top: 10px; }
  /* Buttons */
  button.primary { background: #007bff; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer; user-select:none;}
  button.primary:hover { background: #0056b3; }
  a.link { color:#007bff; cursor:pointer; text-decoration:underline; user-select:none; }
  a.link:hover { color:#0056b3; }
  /* Responsive */
  @media (max-width:600px){
    #profileHeader { flex-direction: column; align-items: flex-start;}
    #profileStats { justify-content: flex-start;}
  }
</style>
</head>
<body>

<header>
  <div>
    <select id="languageSelector" aria-label="Language selector">
      <option value="en">English</option>
      <option value="hu">Magyar</option>
      <option value="mk">Македонски</option>
    </select>
  </div>
  <nav id="navMain">
    <button id="navGames">Games</button>
    <button id="navMarketplace">Marketplace</button>
    <button id="navBuild">Build</button>
    <button id="navNews">News</button>
    <button id="navRanking">Ranking</button>
  </nav>
  <div id="authButtons">
    <button id="btnLogin">Login</button>
    <button id="btnSignUp">Sign Up</button>
  </div>
</header>

<main>
  <!-- LOGIN -->
  <section id="loginSection" class="hidden">
    <h2 id="loginTitle">Login</h2>
    <form id="loginForm">
      <label for="loginUsername">Username:</label>
      <input type="text" id="loginUsername" required autocomplete="username" />
      <label for="loginPassword">Password:</label>
      <input type="password" id="loginPassword" required autocomplete="current-password" />
      <button type="submit" class="primary" id="loginSubmit">Login</button>
      <p id="loginError" style="color:red;"></p>
      <p><span class="link" id="toSignUp">Don't have an account? Sign Up</span></p>
    </form>
  </section>

  <!-- SIGN UP -->
  <section id="signUpSection" class="hidden">
    <h2 id="signUpTitle">Sign Up</h2>
    <form id="signUpForm">
      <p>Select your character:</p>
      <div class="avatars" id="avatarsContainer">
        <!-- Avatars will be injected here -->
      </div>
      <div class="form-group">
        <label for="signUpUsername">Username:</label>
        <input type="text" id="signUpUsername" required autocomplete="username" />
      </div>
      <div class="form-group">
        <label for="signUpEmail">Email (optional):</label>
        <input type="email" id="signUpEmail" autocomplete="email" />
      </div>
      <div class="form-group">
        <label for="signUpCountry">Country:</label>
        <select id="signUpCountry" required>
          <option value="">Select country</option>
          <option value="PL">Poland</option>
          <option value="HU">Hungary</option>
          <option value="MK">Macedonia</option>
          <option value="US">USA</option>
          <option value="DE">Germany</option>
        </select>
      </div>
      <div class="form-group">
        <label for="signUpPassword">Password:</label>
        <input type="password" id="signUpPassword" required autocomplete="new-password" />
      </div>
      <div class="form-group">
        <label for="signUpBirthdate">Birthdate:</label>
        <input type="date" id="signUpBirthdate" required />
      </div>
      <button type="submit" class="primary">Register</button>
      <p id="signUpError" style="color:red;"></p>
      <p><span class="link" id="toLogin">Already have an account? Login</span></p>
    </form>
  </section>

  <!-- PROFILE -->
  <section id="profileSection" class="hidden" tabindex="0">
    <div id="profileHeader">
      <div id="profileAvatar"><img src="" alt="User avatar" /></div>
      <div id="profileInfo">
        <h2 id="profileUsername"></h2>
        <p id="profileCountry"></p>
        <p><strong>Ranking XP place:</strong> <span id="profileRankingPlace"></span></p>
        <div id="profileStats">
          <div>XP: <span id="profileXP"></span></div>
          <div>Friends: <span id="profileFriendsCount"></span></div>
          <div>Gold: <span id="profileGold"></span></div>
          <div>Level: <span id="profileLevel"></span></div>
        </div>
      </div>
    </div>

    <div id="tabs" role="tablist" aria-label="Profile sections">
      <button role="tab" data-tab="gamesTab" class="active" aria-selected="true">Games</button>
      <button role="tab" data-tab="marketplaceTab" aria-selected="false">Marketplace</button>
      <button role="tab" data-tab="buildTab" aria-selected="false">Build</button>
      <button role="tab" data-tab="newGameTab" aria-selected="false">New Game</button>
      <button role="tab" data-tab="newsTab" aria-selected="false">News</button>
      <button role="tab" data-tab="rankingTab" aria-selected="false">Ranking</button>
      <button id="btnLogout" style="margin-left:auto; background:#dc3545; color:white; border:none; padding: 8px 12px; border-radius: 6px; cursor:pointer;">Logout</button>
    </div>

    <!-- Tab Contents -->
    <section id="gamesTab" class="tabContent active" role="tabpanel" tabindex="0">
      <h3>Games</h3>
      <p>Welcome to your games area! Here you can start or continue your games.</p>
      <button id="startGameBtn" class="primary">Start New Game</button>
    </section>

    <section id="marketplaceTab" class="tabContent" role="tabpanel" tabindex="0">
      <h3>Marketplace</h3>
      <p>Buy and sell items here.</p>
      <p><em>Marketplace is under construction.</em></p>
    </section>

    <section id="buildTab" class="tabContent" role="tabpanel" tabindex="0">
      <h3>Build</h3>
      <p>Create and customize your in-game world.</p>
      <p><em>Build section is under construction.</em></p>
    </section>

    <section id="newGameTab" class="tabContent" role="tabpanel" tabindex="0">
      <h3>New Game</h3>
      <p>Create a new game or tournament here.</p>
      <p><em>Feature coming soon.</em></p>
    </section>

    <section id="newsTab" class="tabContent" role="tabpanel" tabindex="0">
      <h3>News</h3>
      <p>Latest news and updates.</p>
      <p><em>No news at the moment.</em></p>
    </section>

    <section id="rankingTab" class="tabContent" role="tabpanel" tabindex="0">
      <h3>Ranking</h3>
      <table id="rankingTable" aria-label="User ranking table">
        <thead>
          <tr>
            <th>Place</th><th>Username</th><th>XP</th><th>Level</th>
          </tr>
        </thead>
        <tbody>
          <!-- Ranking rows inserted by JS -->
        </tbody>
      </table>
    </section>

  </section>

</main>

<script>
(() => {
  // --- Data and state ---
  const LANG = {
    en: {
      login: "Login",
      signup: "Sign Up",
      username: "Username",
      password: "Password",
      email: "Email (optional)",
      country: "Country",
      birthdate: "Birthdate",
      selectCharacter: "Select your character:",
      dontHaveAccount: "Don't have an account? Sign Up",
      alreadyHaveAccount: "Already have an account? Login",
      rankingXPPlace: "Ranking XP place:",
      games: "Games",
      marketplace: "Marketplace",
      build: "Build",
      newGame: "New Game",
      news: "News",
      ranking: "Ranking",
      startNewGame: "Start New Game",
      loginError: "Wrong username or password.",
      signUpError: "Please fill all required fields and select a character.",
      logout: "Logout",
    },
    hu: {
      login: "Bejelentkezés",
      signup: "Regisztráció",
      username: "Felhasználónév",
      password: "Jelszó",
      email: "Email (opcionális)",
      country: "Ország",
      birthdate: "Születési dátum",
      selectCharacter: "Válaszd ki a karaktered:",
      dontHaveAccount: "Nincs még fiókod? Regisztrálj",
      alreadyHaveAccount: "Már van fiókod? Jelentkezz be",
      rankingXPPlace: "XP helyezés a ranglistán:",
      games: "Játékok",
      marketplace: "Piac",
      build: "Építés",
      newGame: "Új játék",
      news: "Hírek",
      ranking: "Ranglista",
      startNewGame: "Új játék indítása",
      loginError: "Hibás felhasználónév vagy jelszó.",
      signUpError: "Töltsd ki a kötelező mezőket és válassz karaktert.",
      logout: "Kijelentkezés",
    },
    mk: {
      login: "Најава",
      signup: "Регистрација",
      username: "Корисничко име",
      password: "Лозинка",
      email: "Е-пошта (опционално)",
      country: "Држава",
      birthdate: "Датум на раѓање",
      selectCharacter: "Избери го својот карактер:",
      dontHaveAccount: "Немате сметка? Регистрирајте се",
      alreadyHaveAccount: "Веќе имате сметка? Најавете се",
      rankingXPPlace: "Место на ранг листата по XP:",
      games: "Игри",
      marketplace: "Пазар",
      build: "Изградба",
      newGame: "Нова игра",
      news: "Вести",
      ranking: "Ранг листа",
      startNewGame: "Започни нова игра",
      loginError: "Погрешно корисничко име или лозинка.",
      signUpError: "Ве молиме пополнете ги сите задолжителни полиња и изберете карактер.",
      logout: "Одјави се",
    }
  };

  // --- Avatars for signup ---
  const avatars = [
    {id: 'avatar1', name: 'Knight', src: 'https://i.ibb.co/fpxLtwS/knight.png'},
    {id: 'avatar2', name: 'Mage', src: 'https://i.ibb.co/vYCNjNk/mage.png'},
    {id: 'avatar3', name: 'Archer', src: 'https://i.ibb.co/F47R0q3/archer.png'},
    {id: 'avatar4', name: 'Rogue', src: 'https://i.ibb.co/kGKPvBq/rogue.png'},
  ];

  // Users data (simulate DB) in localStorage key 'PoKreGaM_users'
  // Logged in user key 'PoKreGaM_currentUser'

  // --- Helper functions ---
  const $ = (id) => document.getElementById(id);
  const show = (el) => el.classList.remove('hidden');
  const hide = (el) => el.classList.add('hidden');
  const sanitize = (str) => String(str).replace(/[<>]/g, '');

  // Translate all visible UI texts based on selected language
  function translateUI(lang) {
    const t = LANG[lang];
    // Header buttons
    $('navMain').querySelectorAll('button').forEach((btn) => {
      const map = {
        navGames: t.games,
        navMarketplace: t.marketplace,
        navBuild: t.build,
        navNews: t.news,
        navRanking: t.ranking,
      };
      if (btn.id in map) btn.textContent = map[btn.id];
    });
    // Auth buttons
    $('btnLogin').textContent = t.login;
    $('btnSignUp').textContent = t.signup;
    // Login form
    $('loginTitle').textContent = t.login;
    $('loginForm').querySelector('label[for="loginUsername"]').textContent = t.username + ":";
    $('loginForm').querySelector('label[for="loginPassword"]').textContent = t.password + ":";
    $('loginSubmit').textContent = t.login;
    $('loginError').textContent = "";
    $('toSignUp').textContent = t.dontHaveAccount;

    // Signup form
    $('signUpTitle').textContent = t.signup;
    $('signUpForm').querySelector('p').textContent = t.selectCharacter;
    $('signUpForm').querySelector('label[for="signUpUsername"]').textContent = t.username + ":";
    $('signUpForm').querySelector('label[for="signUpEmail"]').textContent = t.email + ":";
    $('signUpForm').querySelector('label[for="signUpCountry"]').textContent = t.country + ":";
    $('signUpForm').querySelector('label[for="signUpPassword"]').textContent = t.password + ":";
    $('signUpForm').querySelector('label[for="signUpBirthdate"]').textContent = t.birthdate + ":";
    $('signUpError').textContent = "";
    $('toLogin').textContent = t.alreadyHaveAccount;

    // Profile tabs
    const tabs = $('tabs').querySelectorAll('button');
    const tabTexts = [t.games, t.marketplace, t.build, t.newGame, t.news, t.ranking];
    tabs.forEach((btn, i) => {
      if(i < tabTexts.length) btn.textContent = tabTexts[i];
    });
    $('btnLogout').textContent = t.logout;

    // Profile section info
    $('profileRankingPlace').previousSibling.textContent = t.rankingXPPlace + " ";
    $('startGameBtn').textContent = t.startNewGame;

    // Ranking table headers
    const headers = $('rankingTable').querySelectorAll('th');
    headers[0].textContent = "Place";
    headers[1].textContent = t.username;
    headers[2].textContent = "XP";
    headers[3].textContent = "Level";
  }

  // --- Avatar selection for sign up ---
  function renderAvatars() {
    const container = $('avatarsContainer');
    container.innerHTML = '';
    avatars.forEach(a => {
      const div = document.createElement('div');
      div.className = 'avatar';
      div.tabIndex = 0;
      div.dataset.avatarId = a.id;
      div.title = a.name;
      div.innerHTML = `<img src="${a.src}" alt="${a.name}"/><br>${a.name}`;
      container.appendChild(div);
    });
  }

  // --- LocalStorage user handling ---
  function getUsers() {
    return JSON.parse(localStorage.getItem('PoKreGaM_users') || '[]');
  }
  function saveUsers(users) {
    localStorage.setItem('PoKreGaM_users', JSON.stringify(users));
  }
  function getCurrentUser() {
    const username = localStorage.getItem('PoKreGaM_currentUser');
    if(!username) return null;
    const users = getUsers();
    return users.find(u => u.username === username) || null;
  }
  function setCurrentUser(username) {
    if(username) localStorage.setItem('PoKreGaM_currentUser', username);
    else localStorage.removeItem('PoKreGaM_currentUser');
  }
  // --- Utilities ---
  function calculateLevel(xp) {
    return Math.floor(Math.sqrt(xp/10)) + 1;
  }
  // --- Render profile ---
  function renderProfile(user) {
    if(!user) return;
    $('profileAvatar').querySelector('img').src = avatars.find(a => a.id === user.avatarId)?.src || '';
    $('profileAvatar').querySelector('img').alt = user.avatarName || 'User avatar';
    $('profileUsername').textContent = user.username;
    $('profileCountry').textContent = user.country;
    $('profileXP').textContent = user.xp;
    $('profileFriendsCount').textContent = user.friends?.length || 0;
    $('profileGold').textContent = user.gold;
    $('profileLevel').textContent = calculateLevel(user.xp);
    // Ranking place calculation
    const users = getUsers().sort((a,b) => b.xp - a.xp);
    const place = users.findIndex(u => u.username === user.username) + 1;
    $('profileRankingPlace').textContent = place;
  }

  // --- Render ranking table ---
  function renderRankingTable() {
    const tbody = $('rankingTable').querySelector('tbody');
    const users = getUsers().sort((a,b) => b.xp - a.xp);
    tbody.innerHTML = '';
    users.forEach((u,i) => {
      const tr = document.createElement('tr');
      tr.innerHTML = `<td>${i+1}</td><td>${sanitize(u.username)}</td><td>${u.xp}</td><td>${calculateLevel(u.xp)}</td>`;
      tbody.appendChild(tr);
    });
  }

  // --- Clear inputs ---
  function clearInputs(form) {
    form.querySelectorAll('input').forEach(i => i.value = '');
    form.querySelectorAll('select').forEach(s => s.selectedIndex = 0);
  }

  // --- Show/hide sections ---
  function showSection(section) {
    // Hide all main sections except header
    ['loginSection', 'signUpSection', 'profileSection'].forEach(id => {
      if(id === section.id) show($(id));
      else hide($(id));
    });
  }

  // --- Selected avatar for signup ---
  let selectedAvatarId = null;

  // --- Init app ---
  function init() {
    // Fill avatars
    renderAvatars();

    // On avatar click
    $('avatarsContainer').addEventListener('click', e => {
      let target = e.target;
      while(target && !target.classList.contains('avatar')) {
        target = target.parentElement;
      }
      if(target) {
        // Remove previous selection
        document.querySelectorAll('.avatar.selected').forEach(el => el.classList.remove('selected'));
        target.classList.add('selected');
        selectedAvatarId = target.dataset.avatarId;
      }
    });
    // Also keyboard select avatar
    $('avatarsContainer').addEventListener('keydown', e => {
      if(e.key === 'Enter' || e.key === ' ') {
        e.preventDefault();
        e.target.click();
      }
    });

    // Show login form initially or profile if logged in
    const currentUser = getCurrentUser();
    if(currentUser) {
      showSection($('profileSection'));
      renderProfile(currentUser);
      renderRankingTable();
    } else {
      showSection($('loginSection'));
    }

    // Language selection
    const langSelector = $('languageSelector');
    let currentLang = langSelector.value;
    translateUI(currentLang);
    langSelector.addEventListener('change', () => {
      currentLang = langSelector.value;
      translateUI(currentLang);
    });

    // Navigation tabs
    $('tabs').addEventListener('click', e => {
      if(e.target.tagName !== 'BUTTON') return;
      const tab = e.target;
      const allTabs = Array.from($('tabs').querySelectorAll('button'));
      const tabContents = Array.from(document.querySelectorAll('section.tabContent'));
      allTabs.forEach(t => {
        t.classList.remove('active');
        t.setAttribute('aria-selected', 'false');
      });
      tabContents.forEach(tc => tc.classList.remove('active'));
      tab.classList.add('active');
      tab.setAttribute('aria-selected', 'true');
      const targetId = tab.dataset.tab;
      if(targetId) {
        $(targetId).classList.add('active');
      }
    });

    // Nav buttons in header (simulate switching main content to profile tabs)
    $('navGames').addEventListener('click', () => {
      showSection($('profileSection'));
      activateTab('gamesTab');
    });
    $('navMarketplace').addEventListener('click', () => {
      showSection($('profileSection'));
      activateTab('marketplaceTab');
    });
    $('navBuild').addEventListener('click', () => {
      showSection($('profileSection'));
      activateTab('buildTab');
    });
    $('navNews').addEventListener('click', () => {
      showSection($('profileSection'));
      activateTab('newsTab');
    });
    $('navRanking').addEventListener('click', () => {
      showSection($('profileSection'));
      activateTab('rankingTab');
    });

    // Activate tab helper
    function activateTab(id) {
      const allTabs = Array.from($('tabs').querySelectorAll('button'));
      const tabContents = Array.from(document.querySelectorAll('section.tabContent'));
      allTabs.forEach(t => {
        t.classList.remove('active');
        t.setAttribute('aria-selected', 'false');
      });
      tabContents.forEach(tc => tc.classList.remove('active'));
      const tab = $(`tabs`).querySelector(`button[data-tab="${id}"]`);
      if(tab) {
        tab.classList.add('active');
        tab.setAttribute('aria-selected', 'true');
      }
      const content = $(id);
      if(content) content.classList.add('active');
    }

    // Login / SignUp toggles
    $('toSignUp').addEventListener('click', () => {
      clearInputs($('loginForm'));
      showSection($('signUpSection'));
      selectedAvatarId = null;
      document.querySelectorAll('.avatar.selected').forEach(el => el.classList.remove('selected'));
    });
    $('toLogin').addEventListener('click', () => {
      clearInputs($('signUpForm'));
      showSection($('loginSection'));
    });

    // Login form submit
    $('loginForm').addEventListener('submit', e => {
      e.preventDefault();
      const username = sanitize($('loginUsername').value.trim());
      const password = $('loginPassword').value;
      const users = getUsers();
      const user = users.find(u => u.username.toLowerCase() === username.toLowerCase());
      if(user && user.password === password) {
        setCurrentUser(user.username);
        renderProfile(user);
        renderRankingTable();
        showSection($('profileSection'));
        $('loginError').textContent = '';
        clearInputs($('loginForm'));
      } else {
        $('loginError').textContent = LANG[currentLang].loginError;
      }
    });

    // Signup form submit
    $('signUpForm').addEventListener('submit', e => {
      e.preventDefault();
      const username = sanitize($('signUpUsername').value.trim());
      const email = sanitize($('signUpEmail').value.trim());
      const country = $('signUpCountry').value;
      const password = $('signUpPassword').value;
      const birthdate = $('signUpBirthdate').value;

      if(!username || !country || !password || !birthdate || !selectedAvatarId) {
        $('signUpError').textContent = LANG[currentLang].signUpError;
        return;
      }
      // Check if username exists
      const users = getUsers();
      if(users.some(u => u.username.toLowerCase() === username.toLowerCase())) {
        $('signUpError').textContent = 'Username already exists.';
        return;
      }
      // Create new user object
      const avatar = avatars.find(a => a.id === selectedAvatarId);
      const newUser = {
        username,
        email,
        country,
        password,
        birthdate,
        avatarId: avatar.id,
        avatarName: avatar.name,
        xp: 0,
        gold: 100,
        friends: [],
      };
      users.push(newUser);
      saveUsers(users);
      setCurrentUser(username);
      renderProfile(newUser);
      renderRankingTable();
      showSection($('profileSection'));
      clearInputs($('signUpForm'));
      selectedAvatarId = null;
      document.querySelectorAll('.avatar.selected').forEach(el => el.classList.remove('selected'));
      $('signUpError').textContent = '';
    });

    // Logout
    $('btnLogout').addEventListener('click', () => {
      setCurrentUser(null);
      showSection($('loginSection'));
    });

    // Start New Game button
    $('startGameBtn').addEventListener('click', () => {
      alert('Start new game functionality is coming soon!');
    });
  }

  document.addEventListener('DOMContentLoaded', init);
})();
</script>

<style>
  /* Basic styles for layout */
  body {
    font-family: Arial, sans-serif;
    margin: 0; padding: 0;
    background: #f0f0f0;
  }
  header {
    background: #222;
    color: #fff;
    padding: 1em;
    display: flex; justify-content: space-between; align-items: center;
  }
  header h1 {
    margin: 0;
  }
  nav button {
    background: transparent;
    border: none;
    color: white;
    margin: 0 0.5em;
    font-size: 1em;
    cursor: pointer;
  }
  nav button:hover, nav button.active {
    text-decoration: underline;
  }
  main {
    padding: 1em;
  }
  .hidden {
    display: none;
  }
  form label {
    display: block;
    margin-top: 0.5em;
  }
  form input, form select {
    width: 100%;
    padding: 0.3em;
    margin-top: 0.2em;
  }
  button.primary {
    background: #007bff;
    border: none;
    color: white;
    padding: 0.5em 1em;
    cursor: pointer;
    margin-top: 1em;
  }
  button.primary:hover {
    background: #0056b3;
  }
  .avatar {
    display: inline-block;
    border: 2px solid transparent;
    margin: 0.2em;
    padding: 0.2em;
    cursor: pointer;
    text-align: center;
  }
  .avatar.selected {
    border-color: #007bff;
  }
  .avatar img {
    width: 50px;
    height: 50px;
  }
  #profileAvatar img {
    width: 80px;
    height: 80px;
  }
  #tabs {
    margin-top: 1em;
  }
  #tabs button {
    margin-right: 0.5em;
    padding: 0.5em 1em;
    cursor: pointer;
    background: #ddd;
    border: 1px solid #ccc;
    border-bottom: none;
  }
  #tabs button.active {
    background: white;
    border-bottom: 2px solid #007bff;
  }
  section.tabContent {
    background: white;
    border: 1px solid #ccc;
    padding: 1em;
    margin-top: -1px;
    display: none;
  }
  section.tabContent.active {
    display: block;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 1em;
  }
  th, td {
    border: 1px solid #ccc;
    padding: 0.5em;
    text-align: left;
  }
</style>

<!-- HTML and JS for a game called PoKreGaM with working buttons and profile, login, signup -->

