![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
<section class="project-grid">\
    <div class="projects-intro">
        <h2>Featured Projects</h2>
        <p>Click any project to expand its details, see code links, and swap in your own work.</p>
    </div>

    <article class="project-card">
        <div class="card-header">
            <div>
                <h3>Henry's Portfolio</h3>
                <p class="project-tag">React • API • Charts</p>
            </div>
            <button class="toggle-btn" aria-expanded="false">Details ▾</button>
        </div>
        <div class="card-body">
            <p class="summary">Interactive weather analytics app with live forecasts, temperature trends, and alerts.</p>
            <div class="dropdown-panel">
                <p><strong>Project details:</strong> Real-time data, responsive design, reusable components.</p>
                <p><strong>Code link:</strong> <a href="#" target="_blank" rel="noopener">GitHub repo</a></p>
                <p><strong>Skills:</strong> React, API integration, responsive UI.</p>
            </div>
        </div>
        <img src="https://via.placeholder.com/480x260/5a8cff/ffffff?text=Henry%27s+Portfolio" alt="Henry's Portfolio screenshot">
    </article>

    <article class="project-card">
        <div class="card-header">
            <div>
                <h3>TaskFlow Pro</h3>
                <p class="project-tag">UI • Productivity • State</p>
            </div>
            <button class="toggle-btn" aria-expanded="false">Details ▾</button>
        </div>
        <div class="card-body">
            <p class="summary">A productivity workspace for tracking tasks, deadlines, and team progress.</p>
            <div class="dropdown-panel">
                <p><strong>Project details:</strong> Task boards, calendar reminders, responsive layout.</p>
                <p><strong>Code link:</strong> <a href="#" target="_blank" rel="noopener">GitHub repo</a></p>
                <p><strong>Skills:</strong> State management, responsive design, UI polish.</p>
            </div>
        </div>
        <img src="https://via.placeholder.com/480x260/ff7b72/ffffff?text=TaskFlow+Pro" alt="TaskFlow Pro screenshot">
    </article>

    <article class="project-card">
        <div class="card-header">
            <div>
                <h3>RecipeRadar</h3>
                <p class="project-tag">Search • Backend • Performance</p>
            </div>
            <button class="toggle-btn" aria-expanded="false">Details ▾</button>
        </div>
        <div class="card-body">
            <p class="summary">A culinary search engine that recommends recipes based on ingredients and preferences.</p>
            <div class="dropdown-panel">
                <p><strong>Project details:</strong> Real-time filters, step-by-step cooking cards, optimized image rendering.</p>
                <p><strong>Code link:</strong> <a href="#" target="_blank" rel="noopener">GitHub repo</a></p>
                <p><strong>Skills:</strong> API integration, performance tuning, UX design.</p>
            </div>
        </div>
        <img src="https://via.placeholder.com/480x260/6ee7b7/0f172a?text=RecipeRadar" alt="RecipeRadar screenshot">
    </article>
</section>

<style>
    .project-grid {
        padding: 2.5rem;
        max-width: 1200px;
        margin: 0 auto;
        background: radial-gradient(circle at top left, #111827 0%, #0b1120 60%, #05080f 100%);
        color: #eef2ff;
        font-family: Inter, system-ui, sans-serif;
    }

    .projects-intro {
        text-align: center;
        margin-bottom: 2rem;
    }

    .projects-intro h2 {
        font-size: clamp(2rem, 2.8vw, 3rem);
        letter-spacing: 0.1em;
        color: #a5b4fc;
        margin-bottom: 0.6rem;
    }

    .projects-intro p {
        max-width: 720px;
        margin: 0 auto;
        color: #cbd5e1;
        font-size: 1rem;
    }

    .project-card {
        background: rgba(15, 23, 42, 0.95);
        border: 1px solid rgba(165, 180, 252, 0.15);
        box-shadow: 0 30px 60px rgba(0, 0, 0, 0.28);
        border-radius: 28px;
        overflow: hidden;
        margin: 1rem 0;
        transition: transform 0.25s ease, border-color 0.25s ease, background 0.25s ease;
    }

    .project-card:hover {
        transform: translateY(-8px);
        border-color: #7c3aed;
        background: rgba(15, 23, 42, 1);
    }

    .card-header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 1rem;
        padding: 1.5rem 1.75rem 0.75rem;
    }

    .card-header h3 {
        margin: 0;
        font-size: 1.6rem;
        color: #e2e8f0;
    }

    .project-tag {
        margin: 0.35rem 0 0;
        color: #a5b4fc;
        font-size: 0.95rem;
        letter-spacing: 0.02em;
    }

    .toggle-btn {
        border: none;
        background: rgba(99, 102, 241, 0.14);
        color: #eef2ff;
        padding: 0.85rem 1rem;
        border-radius: 999px;
        cursor: pointer;
        font-size: 0.95rem;
        transition: background 0.2s ease, transform 0.2s ease;
    }

    .toggle-btn:hover {
        background: rgba(124, 58, 237, 0.22);
        transform: translateY(-1px);
    }

    .card-body {
        padding: 0 1.75rem 1.5rem;
    }

    .summary {
        margin: 0;
        color: #cbd5e1;
        line-height: 1.75;
    }

    .dropdown-panel {
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.3s ease, padding 0.3s ease;
        padding: 0 0;
    }

    .dropdown-panel.open {
        max-height: 260px;
        padding-top: 1rem;
    }

    .dropdown-panel p {
        margin: 0.55rem 0;
        color: #dbeafe;
        line-height: 1.8;
    }

    .dropdown-panel a {
        color: #93c5fd;
        text-decoration: none;
    }

    .dropdown-panel a:hover {
        text-decoration: underline;
    }

    .project-card img {
        width: 100%;
        display: block;
        object-fit: cover;
        border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    @media (min-width: 860px) {
        .project-grid {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 1.5rem;
        }

        .project-card {
            margin: 0;
        }

        .project-card:nth-child(odd) img {
            min-height: 250px;
        }
    }

    @media (min-width: 1200px) {
        .project-grid {
            grid-template-columns: repeat(3, minmax(0, 1fr));
        }
    }
</style>

<script>
    document.querySelectorAll('.toggle-btn').forEach(button => {
        button.addEventListener('click', () => {
            const panel = button.closest('.project-card').querySelector('.dropdown-panel');
            const isOpen = panel.classList.toggle('open');
            button.setAttribute('aria-expanded', isOpen);
            button.textContent = isOpen ? 'Hide Details ▴' : 'Details ▾';
        });
    });
</script>
