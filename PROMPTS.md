1. Prompt one: Here is a screenshot of a webpage. I want to create a FAQ section here in the "something missing" section. now write me a prompt so I can copy and paste to a AI code generator 

2. generated prompt: Act as an expert frontend developer. Generate a clean, responsive FAQ section for a tech conference named DevConf 2026 using pure HTML5 and CSS3. The design should match a modern developer portfolio style, using a professional color scheme with blue and orange accents, clear scannable typography, and smooth interaction states.

Generated code (html):
       <!-- ==========================================
       AI CHALLENGE SECTION: FAQ 
       ========================================== -->
    <section class="faq-section">
        <h2 class="section-title">Frequently Asked Questions</h2>
        <p class="section-subtitle">Everything you need to know about DevConf 2026.</p>
        
        <div class="faq-grid">
            <div class="faq-item">
                <h4><i class="fa-solid fa-circle-question"></i> Will the sessions be recorded?</h4>
                <p>Yes! All presentations and keynotes will be recorded. Access depends on your ticket tier, with Pro and Team passes getting extended access.</p>
            </div>
            
            <div class="faq-item">
                <h4><i class="fa-solid fa-circle-question"></i> Are there student discounts available?</h4>
                <p>Absolutely. We offer a 50% discount for verified university students. Please reach out via our contact form with your academic credentials.</p>
            </div>
            
            <div class="faq-item">
                <h4><i class="fa-solid fa-circle-question"></i> Can I transfer my ticket to someone else?</h4>
                <p>Yes, tickets can be transferred to another individual up to 7 days before the event starts. Just contact our support team with your order reference.</p>
            </div>
            
            <div class="faq-item">
                <h4><i class="fa-solid fa-circle-question"></i> Is lunch provided during the conference?</h4>
                <p>Standard, Pro, and Team passes all include catering, full networking lunches, and coffee refills throughout all 3 days of the event.</p>
            </div>
        </div>
    </section>

    <!-- ==========================================
       MANDATORY FOOTER SECTION
       ========================================== -->
    <footer class="main-footer">
        <div class="footer-top">
            <div class="footer-logo">
                💻 DEVCONF <strong>2026</strong>
            </div>
            <div class="footer-socials">
                <a href="https://instagram.com" target="_blank"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://facebook.com" target="_blank"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="https://wa.me" target="_blank"><i class="fa-brands fa-whatsapp"></i></a>
            </div>
        </div>
        
        <hr class="footer-divider">
        
        <div class="footer-bottom">
            <p>&copy; 2026 DevConf. All rights reserved. Designed for Assignment-001.</p>
        </div>
    </footer>






    

   Generated code (css): 
   /* ==========================================================================
   AI CHALLENGE FAQ SECTION STYLES
   ========================================================================== */
.faq-section {
    padding: 80px 8%;
    max-width: 1200px;
    margin: 0 auto;
}

.faq-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
    margin-top: 40px;
}

.faq-item {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    padding: 25px;
    border-radius: 8px;
    transition: transform 0.2s, border-color 0.2s;
}

.faq-item:hover {
    transform: translateY(-3px);
    border-color: #2563eb; /* Highlights blue on hover */
}

.faq-item h4 {
    font-size: 1.1rem;
    color: #0f172a;
    margin-bottom: 10px;
    display: flex;
    align-items: center;
    gap: 10px;
}

.faq-item h4 i {
    color: #fd6e0a; /* Orange question marks icons */
}

.faq-item p {
    color: #475569;
    font-size: 0.95rem;
    line-height: 1.6;
}

/* ==========================================================================
   ASSIGNMENT MANDATORY FOOTER STYLES
   ========================================================================== */
.main-footer {
    background-color: #0f172a;
    color: #94a3b8;
    padding: 40px 8% 20px 8%;
    border-top: 1px solid #1e293b;
}

.footer-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 25px;
}

.footer-logo {
    font-size: 1.2rem;
    color: #ffffff;
    font-weight: 600;
}

.footer-socials {
    display: flex;
    gap: 20px;
}

.footer-socials a {
    color: #94a3b8;
    font-size: 1.3rem;
    transition: color 0.2s, transform 0.2s;
}

.footer-socials a:hover {
    color: #fd6e0a; /* Switches to bright orange on mouse hover */
    transform: scale(1.15);
}

.footer-divider {
    border: 0;
    height: 1px;
    background: #1e293b;
    margin-bottom: 20px;
}

.footer-bottom {
    text-align: center;
    font-size: 0.85rem;
    color: #64748b;
}

/* Responsive adjustment for small monitors */
@media (max-width: 768px) {
    .faq-grid {
        grid-template-columns: 1fr;
    }
    .footer-top {
        flex-direction: column;
        gap: 20px;
        text-align: center;
    }
}