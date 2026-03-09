# Le Bureau Exécutif


## Mandat 2025-2026 : Stratégie & Exécution

Le Bureau Exécutif coordonne l'ensemble des activités d'AéroENSEM, de la conception technique à la gestion des partenariats industriels. Notre mission principale est d'assurer l'allocation optimale des ressources pour nos projets de recherche (systèmes embarqués, aéronautique, IA) et de garantir la livraison des cahiers des charges dans des délais rigoureux.

**Axes stratégiques actuels :**
- **R&D Appliquée** : Pilotage des projets techniques à fort impact (Logistique d'urgence spatiale, conception de drones de surveillance).
- **Synergie Industrielle** : Consolidation des relations avec les acteurs de l'aéronautique marocaine pour financer nos recherches.
- **Transmission** : Formation continue des membres de l'ENSEM aux standards d'ingénierie professionnels.

---

<style>
/* Grid Container for Roles */
.board-grid {
    display: grid;
    gap: 2rem;
    margin-bottom: 3rem;
    justify-content: center;
}

/* Row specifically for P & VP (2 columns max) */
.row-pvp {
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
}

/* Row for Tech, Formations, Sponsoring (3 columns) */
.row-tech {
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

/* Row for Events, Events, Logistics (3 columns) */
.row-events {
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

/* Row for Media, Media (2 columns max) */
.row-media {
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
}

/* Individual Card Styling */
.board-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    background: var(--entry-background);
    padding: 1.5rem;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    transition: transform 0.2s ease-in-out;
    position: relative;
}

.board-card:hover {
    transform: translateY(-5px);
}

/* Circular Responsive Photo Container */
.photo-container {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    overflow: hidden;
    margin-bottom: 1rem;
    border: 4px solid var(--theme);
    flex-shrink: 0;
}

/* Force image to cover the circle regardless of its dimensions */
.photo-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    margin: 0 !important;
}

/* Text Content */
.card-content {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    justify-content: space-between;
}

.card-content h3 {
    margin: 0.5rem 0 0.2rem 0 !important;
    font-size: 1.25rem;
}

.role-title {
    font-weight: bold;
    color: var(--theme);
    font-size: 0.95rem;
    margin-bottom: 1rem;
}

.slogan {
    font-style: italic;
    font-size: 0.9rem;
    opacity: 0.85;
    line-height: 1.4;
    margin-bottom: 1.5rem;
}

/* Social & Contact Links */
.contact-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: auto;
}

.contact-links a {
    color: var(--theme);
    font-size: 1.2rem;
    transition: color 0.2s;
    text-decoration: none;
}

.contact-links a:hover {
    opacity: 0.8;
}

/* Department Descriptions */
.department-desc {
    font-size: 1rem;
    margin-bottom: 2rem;
    padding: 1rem;
    background-color: rgba(0, 0, 0, 0.03);
    border-left: 4px solid var(--theme);
    border-radius: 0 8px 8px 0;
}

/* CTA Footer Styling */
.cta-footer {
    text-align: center;
    padding: 3rem 1.5rem;
    background: var(--entry-background);
    border-radius: 12px;
    margin-top: 4rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
}

.cta-button {
    display: inline-block;
    margin-top: 1.5rem;
    padding: 0.8rem 2rem;
    background-color: var(--theme);
    color: white !important;
    font-weight: bold;
    border-radius: 30px;
    text-decoration: none;
    transition: background-color 0.2s, transform 0.2s;
}

.cta-button:hover {
    filter: brightness(110%);
    transform: translateY(-2px);
}
</style>

## La Direction Stratégique

<div class="department-desc">
    La Présidence et Vice-Présidence définissent l'orientation à long terme du club, agissant comme l'interface décisionnelle principale face aux directions académiques de l'ENSEM et aux autorités industrielles.
</div>

<div class="board-grid row-pvp">
    <!-- Président -->
    <div class="board-card">
        <div class="photo-container">
            <img src="aboudrar.jpg" alt="ABOUDRAR Younes">
        </div>
        <div class="card-content">
            <div>
                <h3>ABOUDRAR Younes</h3>
                <div class="role-title">Président</div>
                <div class="slogan">"Chaque vol commence par un premier pas en avant."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/younes-aboudrar/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:younes.aboudrar.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
    <!-- Vice-Présidente -->
    <div class="board-card">
        <div class="photo-container">
            <img src="bel-kadi.jpg" alt="BEL-KADI Soumia">
        </div>
        <div class="card-content">
            <div>
                <h3>BEL-KADI Soumia</h3>
                <div class="role-title">Vice-Présidente</div>
                <div class="slogan">"Une fois que vous aurez goûté au vol, vous marcherez à jamais les yeux tournés vers le ciel."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/soumia-belkadi-496ba434b/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:soumia.bel-kadi.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
</div>

---

## Le Pôle Technique, Formations & Partenariats

<div class="department-desc">
    Ce macro-département est le moteur d'AéroENSEM. Ici, les concepts théoriques deviennent des prototypes fonctionnels. Il rassemble nos chefs de projets (CAO, CFD, Systèmes Embarqués), nos formateurs, et le pôle Sponsoring chargé de financer ces innovations.
</div>

<div class="board-grid row-tech">
    <!-- Chef de Projets -->
    <div class="board-card">
        <div class="photo-container">
            <img src="faqihi.jpg" alt="FAQIHI Ayoub">
        </div>
        <div class="card-content">
            <div>
                <h3>FAQIHI Ayoub</h3>
                <div class="role-title">Chef de Projets</div>
                <div class="slogan">"Un test vaut mille prédictions."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/ayoub-faqihi-693715368/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:ayoub.faqihi.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
    <!-- Sponsoring -->
    <div class="board-card">
        <div class="photo-container">
            <img src="maataoui.jpg" alt="MAATAOUI Fahd">
        </div>
        <div class="card-content">
            <div>
                <h3>MAATAOUI Fahd</h3>
                <div class="role-title">Responsable Sponsoring</div>
                <div class="slogan">"Soutenir l'ingénierie étudiante, c'est financer la souveraineté de notre industrie."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/fahd-maataoui-50698b35a/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:fahd.maataoui.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
    <!-- Formations -->
    <div class="board-card">
        <div class="photo-container">
            <img src="kamoune.jpg" alt="KAMOUNE Yahya">
        </div>
        <div class="card-content">
            <div>
                <h3>KAMOUNE Yahya</h3>
                <div class="role-title">Responsable de Formations</div>
                <div class="slogan">"Chaque minute passée à apprendre est un pas de plus vers l’excellence."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/yahya-kamoune-a0423524b/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:yahya.kamoune.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
</div>

---

## Événements & Logistique

<div class="department-desc">
    Ce pôle assure la gestion de la chaîne logistique, l'allocation du matériel technique (budget, capteurs, outillage), et la planification opérationnelle complète de nos grandes conférences comme la JAE, incluant la gestion des relations avec les conférenciers industriels.
</div>

<div class="board-grid row-events">
    <!-- Respo Event -->
    <div class="board-card">
        <div class="photo-container">
            <img src="najwa.jpg" alt="BOUHDILA Najoua">
        </div>
        <div class="card-content">
            <div>
                <h3>BOUHDILA Najoua</h3>
                <div class="role-title">Responsable Conférences et Événements</div>
                <div class="slogan">"Nous rassemblons l'industrie aéronautique de demain autour d'une vision commune."</div>
            </div>
             <div class="contact-links">
                <a href="https://www.linkedin.com/in/najoua-bouhdila-236878277/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:najoua.bouhdila.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
    <!-- Co-Respo Event -->
    <div class="board-card">
        <div class="photo-container">
            <img src="guourch.jpg" alt="GUOURCH Mohammed">
        </div>
        <div class="card-content">
            <div>
                <h3>GUOURCH Mohammed</h3>
                <div class="role-title">Co-Responsable Conférences et Événements</div>
                <div class="slogan">"L'innovation prend tout son sens lorsqu'elle est partagée avec le monde industriel."</div>
            </div>
             <div class="contact-links">
                <a href="https://www.linkedin.com/in/mohammed-guourch-16a529212/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:mohammed.guourch.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
    <!-- Logistique -->
    <div class="board-card">
        <div class="photo-container">
            <img src="belkacem.jpg" alt="BELKACEM Ilyas">
        </div>
        <div class="card-content">
            <div>
                <h3>BELKACEM Ilyas</h3>
                <div class="role-title">Responsable Logistique et Mobilisation</div>
                <div class="slogan">"La logistique est le moteur silencieux qui transforme les rêves en réalité."</div>
            </div>
             <div class="contact-links">
                <a href="https://www.linkedin.com/in/belkacem-ilyas-224818340/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:ilyas.belkacem.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
</div>

---

## Image & Média

<div class="department-desc">
    Département en charge de la couverture médiatique nationale, de l'identité visuelle de nos campagnes et de la documentation de nos avancées techniques. "Si l'ingénierie est le corps, la communication en est la voix."
</div>

<div class="board-grid row-media">
    <!-- Media -->
    <div class="board-card">
        <div class="photo-container">
            <img src="radi.jpg" alt="RADI Douae">
        </div>
        <div class="card-content">
            <div>
                <h3>RADI Douae</h3>
                <div class="role-title">Responsable Communication (Design & Média)</div>
                <div class="slogan">"L'excellence technique n'a d'impact que si elle est communiquée avec ambition."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/douae-radi-9149822a9/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:j134348724@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
    <!-- Co-Media -->
    <div class="board-card">
        <div class="photo-container">
            <img src="ramadan.jpg" alt="MUHAMMAD Ramadan">
        </div>
        <div class="card-content">
            <div>
                <h3>MUHAMMAD Ramadan</h3>
                <div class="role-title">Co-Responsable Communication</div>
                <div class="slogan">"Se réunir est un début, rester ensemble est un progrès, travailler ensemble est la réussite."</div>
            </div>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/muhamad-ramadan-99aba3338/" target="_blank" title="Profil LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:muhammadramadan.djibrillamaiga.etu24@ensem.ac.ma" title="Contacter le Président"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>
</div>

---

<div class="cta-footer">
    <h2>Rejoindre les Équipes Opérationnelles</h2>
    <p>L'intégration au sein d'AéroENSEM est conditionnée par un processus de sélection technique et d'évaluation des soft skills. Nous recherchons des profils hautement rationnels, capables de travailler sous pression et de respecter des protocoles stricts.</p>
    <a href="/contact/" class="cta-button">Voir les processus de recrutement</a>
</div>


---

> Auteur: <no value>  
> URL: http://localhost:59322/equipe/  

