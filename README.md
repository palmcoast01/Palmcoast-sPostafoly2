export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-900">
      {/* Header */}
      <header className="p-6 shadow-md bg-white">
        <h1 className="text-3xl font-bold text-indigo-600">Estratega en Marketing & Ventas</h1>
        <p className="text-gray-600">Especialista en Redes Sociales y Crecimiento de Negocios</p>
      </header>

      {/* About Section */}
      <section className="max-w-5xl mx-auto p-8">
        <h2 className="text-2xl font-semibold mb-4">👤 Sobre mí</h2>
        <p>
          Soy un estratega en marketing y ventas con experiencia en la creación de
          campañas digitales que conectan con las emociones de los clientes y generan
          resultados medibles. Mi enfoque combina la analítica de datos con la creatividad
          en redes sociales, logrando construir marcas sólidas y comunidades fieles.
        </p>
      </section>

      {/* Skills Section */}
      <section className="max-w-5xl mx-auto p-8 bg-indigo-50 rounded-2xl my-6">
        <h2 className="text-2xl font-semibold mb-4">🎯 Especialidades</h2>
        <ul className="grid grid-cols-1 md:grid-cols-2 gap-3">
          <li>✔️ Estrategias de marketing digital</li>
          <li>✔️ Embudos de conversión y ventas online</li>
          <li>✔️ Publicidad en Facebook Ads, Instagram Ads y Google Ads</li>
          <li>✔️ Creación y gestión de contenido para redes sociales</li>
          <li>✔️ Email marketing y automatización</li>
          <li>✔️ Análisis de métricas y optimización de ROI</li>
        </ul>
      </section>

      {/* Results Section */}
      <section className="max-w-5xl mx-auto p-8">
        <h2 className="text-2xl font-semibold mb-4">📈 Resultados Destacados</h2>
        <ul className="space-y-2">
          <li>🚀 Aumento del 150% en ventas de e-commerce de moda en 6 meses.</li>
          <li>📊 Multiplicación por 4 de la facturación de un negocio local en 3 meses.</li>
          <li>🎥 Estrategias en TikTok con +500K visualizaciones orgánicas.</li>
          <li>💬 Implementación de chatbots que elevaron la conversión en un 40%.</li>
        </ul>
      </section>

      {/* Tools */}
      <section className="max-w-5xl mx-auto p-8 bg-indigo-50 rounded-2xl my-6">
        <h2 className="text-2xl font-semibold mb-4">🛠️ Herramientas</h2>
        <p>
          Meta Business Suite · Google Ads · Google Analytics · HubSpot · Canva · Photoshop · Notion · Trello
        </p>
      </section>

      {/* Projects Section */}
      <section className="max-w-5xl mx-auto p-8">
        <h2 className="text-2xl font-semibold mb-6">📂 Proyectos Destacados</h2>
        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <div className="bg-white shadow-md rounded-2xl overflow-hidden">
            <img src="https://via.placeholder.com/400x250" alt="Campaña Instagram" className="w-full h-48 object-cover" />
            <div className="p-4">
              <h3 className="font-semibold text-lg">Campaña en Instagram</h3>
              <p className="text-sm text-gray-600">Antes/Después: crecimiento en seguidores y engagement en marca de ropa.</p>
            </div>
          </div>
          <div className="bg-white shadow-md rounded-2xl overflow-hidden">
            <img src="https://via.placeholder.com/400x250" alt="Reel Viral" className="w-full h-48 object-cover" />
            <div className="p-4">
              <h3 className="font-semibold text-lg">Reel Viral en TikTok</h3>
              <p className="text-sm text-gray-600">Superó las 500K visualizaciones orgánicas con estrategia de storytelling.</p>
            </div>
          </div>
          <div className="bg-white shadow-md rounded-2xl overflow-hidden">
            <img src="https://via.placeholder.com/400x250" alt="Dashboard" className="w-full h-48 object-cover" />
            <div className="p-4">
              <h3 className="font-semibold text-lg">Dashboard de Ventas</h3>
              <p className="text-sm text-gray-600">Reporte visual de crecimiento con métricas clave y ROI positivo.</p>
            </div>
          </div>
        </div>
      </section>

      {/* Contact */}
      <section className="max-w-5xl mx-auto p-8">
        <h2 className="text-2xl font-semibold mb-4">📞 Contacto</h2>
        <p>Email: <a href="mailto:tuemail@ejemplo.com" className="text-indigo-600">tuemail@ejemplo.com</a></p>
        <p>WhatsApp: <a href="https://wa.me/57xxxxxxxxxx" className="text-indigo-600">+57 xxx xxx xxxx</a></p>
        <p>LinkedIn: <a href="#" className="text-indigo-600">linkedin.com/in/tuusuario</a></p>
      </section>

      {/* Footer */}
      <footer className="p-6 text-center bg-gray-100 mt-10">
        <p className="text-gray-600">© 2025 Estratega en Marketing & Ventas – Todos los derechos reservados</p>
      </footer>
    </div>
  );
}
