import React, { useState } from 'react';
import { 
  Menu, Info, Utensils, Truck, Share2, MapPin, 
  Phone, Instagram, Facebook, Globe, Clock, ChevronLeft,
  ChevronRight, ExternalLink, ShoppingBag, Star, Flame, X
} from 'lucide-react';

// --- DICTIONARY FOR UI TEXTS ---
const t = {
  en: {
    ourMenu: "Our Menu", ourStory: "Our Story", catering: "Catering", locations: "Locations & Info",
    slogan1: "Slow Smoked.", slogan2: "Real Flavor.", tagline: "Carolina Roots • Florida Soul",
    aboutTitle: "From NC to FL",
    about1: "Originally founded in North Carolina, ",
    about1b: " was born from a passion for authentic southern smoked flavor. After perfecting our recipes and techniques, we decided to take our culinary experience to a new level and a new state.",
    about2: "In ",
    about2b: ", we proudly opened our doors in the vibrant city of ",
    about2c: ". The response from the community was incredible, embracing our slow-smoked meats and homemade sides.",
    aboutNew: "The family is growing! We are thrilled to announce our second location, newly opened in ",
    qualityTitle: "Our Quality",
    qualityText: "Our specialty is traditional BBQ. From juicy smoked Brisket and pulled Pork, to our famous St. Louis ribs. Everything is prepared with premium ingredients and the patience that true BBQ requires.",
    pricesChange: "* Prices subject to change *",
    readyToOrder: "Ready to order?",
    orderToastFt: "Order Toast - Fort Myers",
    orderToastCc: "Order Toast - Cape Coral",
    questions: "Questions? Call Us",
    backToMenu: "Back to Menu",
    caterTitle: "Cater Your Next Event!",
    caterDesc: "From office lunches to extravagant weddings, no catering is too large or too elaborate! Contact us and we'll get back to you in 24 to 48 hours.",
    fullService: "Full Service", fullServiceDesc: "We take care of the smoked meats, sides, and everything you need for a perfect feast.",
    fastResponse: "Fast Response", fastResponseDesc: "Fill out the request form and we'll get back to you with a proposal rapidly.",
    visitWeb: "Or visit our website to fill out the form.",
    ourSpots: "Our Spots", est: "Est. 2022", brandNew: "Brand New",
    monSat: "MON - SAT:", sun: "SUNDAY:", soldOut: "* Or until sold out",
    call: "Call", map: "Map", connect: "Connect",
    mainInsta: "Main Instagram", fmCc: "Fort Myers & Cape Coral",
    fbPage: "Facebook Page", website: "Website",
    rights: "All Rights Reserved."
  },
  es: {
    ourMenu: "Nuestro Menú", ourStory: "Nuestra Historia", catering: "Catering", locations: "Ubicaciones e Info",
    slogan1: "Ahumado Lento.", slogan2: "Sabor Real.", tagline: "Raíces de Carolina • Alma de Florida",
    aboutTitle: "De Carolina a Florida",
    about1: "Originalmente fundado en Carolina del Norte, ",
    about1b: " nació de la pasión por el auténtico sabor del ahumado sureño. Tras perfeccionar nuestras recetas y técnicas, decidimos llevar nuestra experiencia a un nuevo nivel y a un nuevo estado.",
    about2: "En ",
    about2b: ", abrimos orgullosamente nuestras puertas en la vibrante ciudad de ",
    about2c: ". La respuesta de la comunidad fue increíble, abrazando nuestras carnes ahumadas lentamente y nuestros acompañantes caseros.",
    aboutNew: "¡La familia crece! Estamos emocionados de anunciar nuestra segunda locación, recién inaugurada en ",
    qualityTitle: "Nuestra Calidad",
    qualityText: "Nuestra especialidad es el BBQ tradicional. Desde jugosos cortes de Brisket ahumado y Pork desmenuzado, hasta nuestras famosas costillas St. Louis. Todo se prepara con ingredientes premium y la paciencia que exige el verdadero BBQ.",
    pricesChange: "* Precios sujetos a cambios *",
    readyToOrder: "¿Listo para ordenar?",
    orderToastFt: "Pedir Toast - Fort Myers",
    orderToastCc: "Pedir Toast - Cape Coral",
    questions: "¿Dudas? Llámanos",
    backToMenu: "Volver al Menú",
    caterTitle: "¡Atendemos tu Evento!",
    caterDesc: "Desde almuerzos de oficina hasta bodas extravagantes, ¡ningún evento es demasiado grande o elaborado! Contáctanos y te responderemos en 24 a 48 horas.",
    fullService: "Servicio Completo", fullServiceDesc: "Nos encargamos de las carnes ahumadas, los acompañantes y todo lo necesario para un banquete perfecto.",
    fastResponse: "Respuesta Rápida", fastResponseDesc: "Llena el formulario de solicitud y nos comunicaremos contigo con una propuesta rápidamente.",
    visitWeb: "O visita nuestra web para llenar el formulario.",
    ourSpots: "Nuestros Locales", est: "Est. 2022", brandNew: "¡Nuevo!",
    monSat: "LUN - SÁB:", sun: "DOMINGO:", soldOut: "* O hasta agotar existencias",
    call: "Llamar", map: "Mapa", connect: "Conectar",
    mainInsta: "Instagram Principal", fmCc: "Fort Myers y Cape Coral",
    fbPage: "Página de Facebook", website: "Sitio Web",
    rights: "Todos los derechos reservados."
  }
};

// --- DATA: MENU ---
const menuData = [
  {
    category: { en: "BBQ", es: "BBQ (Ahumados)" },
    image: "https://images.unsplash.com/photo-1558030006-450675393462?auto=format&fit=crop&w=800&q=80",
    columns: { en: ["Sandwich [1 Side]", "Platter [2 Sides]"], es: ["Sándwich [1 Acomp.]", "Plato [2 Acomp.]"] },
    items: [
      { name: { en: "Pork", es: "Pork (Cerdo)" }, desc: { en: "Slow-smoked pulled pork, perfectly tender with authentic Carolina flavor.", es: "Cerdo desmenuzado ahumado lentamente, perfectamente tierno con auténtico sabor de Carolina." }, prices: ["$11.49", "$16.49"], image: "" },
      { name: { en: "Jalapeno Cheddar Smoked Sausage", es: "Salchicha Ahumada Jalapeño Cheddar" }, desc: { en: "Savory smoked sausage infused with spicy jalapeno and creamy cheddar cheese.", es: "Sabrosa salchicha ahumada con un toque de jalapeño picante y queso cheddar cremoso." }, prices: ["$12.49", "$16.49"], image: "" },
      { name: { en: "Turkey", es: "Turkey (Pavo)" }, desc: { en: "Juicy, slow-smoked turkey breast sliced thin and piled high.", es: "Jugosa pechuga de pavo ahumada lentamente, cortada fina y apilada." }, prices: ["$12.49", "$16.49"], image: "" },
      { name: { en: "Brisket", es: "Brisket (Pecho de Res)" }, desc: { en: "Our signature slow-smoked beef brisket, sliced tender with a perfect dark bark.", es: "Nuestro característico pecho de res ahumado lentamente, cortado tierno con una corteza oscura perfecta." }, prices: ["$14.49", "$22.49"], image: "https://images.unsplash.com/photo-1628294895950-9805252327bc?auto=format&fit=crop&w=800&q=80" },
      { name: { en: "Brisket Burnt Ends", es: "Brisket Burnt Ends" }, desc: { en: "Caramelized, smoky, flavor-packed nuggets of brisket goodness.", es: "Trocitos de brisket caramelizados, ahumados y llenos de sabor intenso." }, prices: ["$15.99", "$23.49"], image: "" },
    ]
  },
  {
    category: { en: "St. Louis Spare Ribs", es: "Costillas St. Louis" },
    image: "https://images.unsplash.com/photo-1593030668930-8130abedd2b0?auto=format&fit=crop&w=800&q=80",
    subtitle: { en: "[2 Sides]", es: "[2 Acompañantes]" },
    items: [
      { name: { en: "Quarter Rack", es: "Cuarto de Rack" }, desc: { en: "A quarter rack of our tender, dry-rubbed and slow-smoked spare ribs.", es: "Un cuarto de rack de nuestras costillas de cerdo tiernas, sazonadas en seco y ahumadas lentamente." }, prices: ["$16.99"], image: "" },
      { name: { en: "Half Rack", es: "Medio Rack" }, desc: { en: "A generous half rack of our fall-off-the-bone smoked spare ribs.", es: "Un generoso medio rack de nuestras costillas ahumadas que se deshacen en el hueso." }, prices: ["$23.99"], image: "" },
      { name: { en: "Full Rack", es: "Rack Completo" }, desc: { en: "A massive full rack of our signature St. Louis style spare ribs, perfect for sharing.", es: "Un rack completo de nuestras exclusivas costillas St. Louis, perfecto para compartir." }, prices: ["$37.99"], image: "" },
    ]
  },
  {
    category: { en: "Smash-Burgers", es: "Smash-Burgers" },
    image: "https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&q=80&w=800",
    subtitle: { en: "[1 Side]", es: "[1 Acompañante]" },
    items: [
      { name: { en: "Double Cheese", es: "Doble Queso" }, desc: { en: "Two smashed beef patties with melted cheese, served hot on a toasted bun.", es: "Dos patties de res aplastados con queso derretido, servidos calientes en pan tostado." }, prices: ["$13.49"], image: "https://images.unsplash.com/photo-1586190848861-f56b5d1b3333?auto=format&fit=crop&w=800&q=80" },
      { name: { en: "Single Cheese", es: "Queso Sencilla" }, desc: { en: "A classic single smashed beef patty with melted cheese on a toasted bun.", es: "Un patty clásico de res con queso derretido en pan tostado." }, prices: ["$11.49"], image: "" },
    ]
  },
  {
    category: { en: "Specialty Sandwiches", es: "Sándwiches Especiales" },
    image: "https://images.unsplash.com/photo-1612871689353-cccf581d667b?auto=format&fit=crop&w=800&q=80",
    subtitle: { en: "[1 Side]", es: "[1 Acompañante]" },
    items: [
      { name: { en: "Turkey Melt", es: "Turkey Melt" }, desc: { en: "Big Nicks smoked turkey with bacon, melted american cheese, served on a warm potato bun.", es: "Pavo ahumado con tocino, queso americano derretido, en pan de papa caliente." }, prices: ["$15.49"], image: "" },
      { name: { en: "Prime Rib Dip", es: "Prime Rib Dip" }, desc: { en: "Big Nicks prime rib thinly sliced, melted swiss cheese, served with au jus on a toasted hoagie.", es: "Prime rib cortado fino, queso suizo derretido, servido con jugo en pan hoagie tostado." }, prices: ["$16.49"], image: "" },
      { name: { en: "Pastrami Reuben", es: "Pastrami Reuben" }, desc: { en: "Corned beef with sauerkraut, melted swiss cheese and dressing on grilled rye.", es: "Corned beef con chucrut, queso suizo derretido y aderezo en pan de centeno a la parrilla." }, prices: ["$15.99"], image: "" }
    ]
  },
  {
    category: { en: "Signatures & Plates", es: "Especialidades y Platos" },
    image: "https://images.unsplash.com/photo-1600891964092-4316c288032e?auto=format&fit=crop&w=800&q=80",
    items: [
      { name: { en: "Big Nick's Salad", es: "Ensalada Big Nick's" }, desc: { en: "Crisp greens topped with cucumbers, tomatoes, hard boiled egg, bacon and your choice of protein.", es: "Verduras crujientes con pepinos, tomates, huevo duro, tocino y tu elección de proteína ahumada." }, prices: ["$16.49"], image: "" },
      { name: { en: "Brisket Eggroll", es: "Brisket Eggroll" }, desc: { en: "Pimento cheese rolled into a flour wrapper and deep fried.", es: "Queso pimiento envuelto en una tortilla de harina y frito hasta quedar crujiente." }, prices: ["$4.50"], image: "" },
      { name: { en: "2 Meat Plate", es: "Plato de 2 Carnes" }, desc: { en: "Choose 2: Ribs, Brisket, Pork, Turkey or Jalapeno Cheddar Smoked Sausage. Includes 2 Sides.", es: "Elige 2: Costillas, Brisket, Cerdo, Pavo o Salchicha. Incluye 2 Acompañantes." }, prices: ["$22.99"], image: "" },
      { name: { en: "Family Meal Pack [Feeds 6]", es: "Paquete Familiar [Para 6]" }, desc: { en: "Enjoy your choice of 2 meats, 3 sides, bread and a gallon of fresh brewed tea or lemonade.", es: "Disfruta 2 carnes, 3 acompañantes, pan y un galón de té recién hecho o limonada." }, prices: ["$79.99"], image: "" }
    ]
  },
  {
    category: { en: "Tacos [2]", es: "Tacos [2]" },
    image: "https://images.unsplash.com/photo-1551504734-5ee1c4a1479b?auto=format&fit=crop&q=80&w=800",
    subtitle: { en: "[1 Side] Flour tortillas, house made pico de gallo, shredded cheese and crema.", es: "[1 Acomp.] Tortillas de harina, pico de gallo casero, queso rallado y crema." },
    items: [
      { name: { en: "Pork", es: "Pork (Cerdo)" }, desc: { en: "Two soft flour tortillas loaded with smoked pulled pork, fresh pico de gallo, and crema.", es: "Dos tortillas cargadas con cerdo ahumado desmenuzado, pico de gallo fresco y crema." }, prices: ["$12.49"], image: "" },
      { name: { en: "Brisket", es: "Brisket (Pecho de Res)" }, desc: { en: "Two soft flour tortillas packed with chopped smoked brisket, fresh pico de gallo, and crema.", es: "Dos tortillas rellenas de brisket ahumado picado, pico de gallo fresco y crema." }, prices: ["$15.49"], image: "" },
    ]
  },
  {
    category: { en: "Smoked Wings", es: "Alitas Ahumadas" },
    image: "https://images.unsplash.com/photo-1527477396000-e27163b481c2?auto=format&fit=crop&q=80&w=800",
    items: [
      { name: { en: "Each", es: "Unidad (Cada una)" }, desc: { en: "Our signature jumbo chicken wings, perfectly smoked and seasoned.", es: "Nuestras exclusivas alitas de pollo jumbo, perfectamente ahumadas y sazonadas." }, prices: ["$2.49"], image: "" },
      { name: { en: "5 Piece Platter w/ 2 Sides", es: "Plato de 5 Piezas con 2 Acomp." }, desc: { en: "Five of our famous smoked jumbo wings, served with your choice of two sides.", es: "Cinco de nuestras famosas alitas jumbo ahumadas, servidas con dos acompañantes." }, prices: ["$16.99"], image: "" },
      { name: { en: "20 Jumbo Special", es: "Especial 20 Jumbo" }, desc: { en: "A crowd-pleasing platter of twenty smoked jumbo wings.", es: "Una bandeja para multitudes de veinte alitas jumbo ahumadas." }, prices: ["$35.99"], image: "" },
      { name: { en: "40 Jumbo Special", es: "Especial 40 Jumbo" }, desc: { en: "The ultimate wing feast: forty of our signature smoked jumbo wings.", es: "El banquete definitivo: cuarenta de nuestras exclusivas alitas jumbo ahumadas." }, prices: ["$60.99"], image: "" }
    ]
  },
  {
    category: { en: "Sides", es: "Acompañantes" },
    image: "https://images.unsplash.com/photo-1604908176997-125f25cc6f3d?auto=format&fit=crop&q=80&w=800",
    columns: { en: ["Serving", "Pint"], es: ["Porción", "Pinta"] },
    items: [
      { name: { en: "Fried Okra, Waffle Fries, Tater Salad, Baked Beans, Coleslaw, Hushpuppies, Green Beans, Collard Greens", es: "Fried Okra, Waffle Fries, Tater Salad, Baked Beans, Coleslaw, Hushpuppies, Green Beans, Collard Greens" }, desc: { en: "Classic homemade southern sides to perfectly complement your BBQ.", es: "Acompañantes sureños caseros clásicos para complementar perfectamente tu BBQ." }, prices: ["$4.99", "$8.99"], image: "" },
      { name: { en: "Brisket Mac & Cheese", es: "Macarrones con Queso y Brisket" }, desc: { en: "Creamy, cheesy macaroni loaded with savory pieces of our smoked brisket.", es: "Macarrones cremosos con queso, cargados con sabrosos trozos de nuestro brisket ahumado." }, prices: ["$5.99", "$9.99"], image: "" }
    ]
  },
  {
    category: { en: "Desserts", es: "Postres" },
    image: "https://images.unsplash.com/photo-1502004960551-dc67f7c24cb3?auto=format&fit=crop&q=80&w=800",
    items: [
      { name: { en: "Key Lime Pie", es: "Key Lime Pie" }, desc: { en: "A slice of sweet and tart classic Florida Key Lime pie with a graham cracker crust.", es: "Una porción de pastel de limón (Key Lime) clásico de Florida, dulce y ácido." }, prices: ["$6.99"], image: "" },
      { name: { en: "Banana Pudding Pint", es: "Pinta de Pudín de Banana" }, desc: { en: "A whole pint of our rich, creamy banana pudding layered with vanilla wafers.", es: "Una pinta entera de nuestro rico y cremoso pudín de plátano en capas con galletas de vainilla." }, prices: ["$9.99"], image: "" }
    ]
  },
  {
    category: { en: "Soft Drinks", es: "Refrescos y Bebidas" },
    image: "https://images.unsplash.com/photo-1527661591475-527312dd65f5?auto=format&fit=crop&w=800&q=80",
    items: [
      { name: { en: "Fountain Drinks & Tea", es: "Refrescos de Máquina y Té" }, desc: { en: "Coke, Diet Coke, Sprite, Cheerwine, Barq's Root Beer, Lemonade, Sweet Tea, Unsweet Tea.", es: "Coke, Diet Coke, Sprite, Cheerwine, Barq's Root Beer, Limonada, Té Dulce, Té sin endulzar." }, prices: ["$2.49"], image: "" },
      { name: { en: "Gallon Fresh Brewed Tea", es: "Galón de Té Recién Hecho" }, desc: { en: "A full gallon of our freshly brewed sweet or unsweetened tea.", es: "Un galón entero de nuestro té recién hecho, dulce o sin endulzar." }, prices: ["$5.99"], image: "" }
    ]
  },
  {
    category: { en: "Alcoholic Beverages", es: "Bebidas Alcohólicas" },
    image: "https://images.unsplash.com/photo-1538593704904-453086eb2d56?auto=format&fit=crop&w=800&q=80",
    items: [
      { name: { en: "Michelob Ultra", es: "Michelob Ultra" }, desc: { en: "Crisp and refreshing light beer.", es: "Cerveza ligera crujiente y refrescante." }, prices: ["$4.99"], image: "" },
      { name: { en: "Mango Cart", es: "Mango Cart" }, desc: { en: "A light wheat ale bursting with fresh mango flavor.", es: "Una cerveza de trigo ligera que explota con sabor a mango fresco." }, prices: ["$5.99"], image: "" },
      { name: { en: "Kona Big Wave", es: "Kona Big Wave" }, desc: { en: "A lighter-bodied golden ale with a tropical hop aroma and flavor.", es: "Una cerveza dorada de cuerpo ligero con aroma y sabor a lúpulo tropical." }, prices: ["$5.99"], image: "" },
      { name: { en: "Scotty's Irish Red", es: "Scotty's Irish Red" }, desc: { en: "A perfectly balanced Irish red ale.", es: "Una cerveza roja irlandesa perfectamente equilibrada." }, prices: ["$5.99"], image: "" },
      { name: { en: "Surfside", es: "Surfside" }, desc: { en: "Refreshing iced tea & vodka cocktail.", es: "Refrescante cóctel de té helado y vodka." }, prices: ["$4.99"], image: "" },
      { name: { en: "Nutrl", es: "Nutrl" }, desc: { en: "Vodka seltzer with real juice.", es: "Seltzer de vodka con jugo real." }, prices: ["$4.99"], image: "" },
      { name: { en: "Red Wine", es: "Vino Tinto (Red Wine)" }, desc: { en: "A classic glass of red wine.", es: "Una clásica copa de vino tinto." }, prices: ["$5.99"], image: "" },
      { name: { en: "White Wine", es: "Vino Blanco (White Wine)" }, desc: { en: "A chilled glass of crisp white wine.", es: "Una copa fría de vino blanco crujiente." }, prices: ["$5.99"], image: "" }
    ]
  }
];

export default function App() {
  const [currentView, setCurrentView] = useState('home');
  const [selectedItem, setSelectedItem] = useState(null);
  
  // ESTADO PARA EL IDIOMA (Default: Inglés)
  const [lang, setLang] = useState('en');
  
  // ESTADO PARA EL ERROR DEL VIDEO
  const [videoError, setVideoError] = useState(false);

  const goHome = () => setCurrentView('home');

  // --- REUSABLE COMPONENTS ---
  const Header = ({ title, onBack }) => (
    <div className="sticky top-0 bg-zinc-950 shadow-md border-b-2 border-red-700 z-30 px-4 py-4 flex items-center justify-between">
      <div className="flex items-center flex-1">
        <button onClick={onBack} className="p-2 -ml-2 rounded hover:bg-zinc-800 text-zinc-100 transition active:scale-90">
          <ChevronLeft size={28} />
        </button>
        <h1 className="text-xl font-black text-zinc-100 ml-2 tracking-widest uppercase">{title}</h1>
      </div>
      
      {/* Botón de Idioma en Cabecera */}
      <div className="flex bg-zinc-900 border border-zinc-700 rounded-full overflow-hidden shadow-inner">
        <button onClick={() => setLang('en')} className={`px-2 py-1 text-[10px] font-black tracking-widest transition ${lang === 'en' ? 'bg-red-700 text-white' : 'text-zinc-500'}`}>EN</button>
        <button onClick={() => setLang('es')} className={`px-2 py-1 text-[10px] font-black tracking-widest transition ${lang === 'es' ? 'bg-amber-600 text-zinc-900' : 'text-zinc-500'}`}>ES</button>
      </div>
    </div>
  );

  const SectionTitle = ({ children }) => (
    <h2 className="text-2xl font-black text-zinc-100 mb-4 uppercase tracking-wider flex items-center gap-2 border-b border-zinc-800 pb-2">
      {children}
    </h2>
  );

  // =========================================================================
  // --- INTERRUPTOR DE VIDEO ---
  // Cambia `true` por `false` para deshacer el cambio y volver a la foto.
  const USAR_VIDEO_DE_FONDO = true; 
  // Enlace de video de prueba más estable (Carne en la parrilla)
  const VIDEO_URL = "https://joy.videvo.net/videvo_files/video/free/2018-07/large_watermarked/180607_A_091_preview.mp4";
  const FOTO_DE_FONDO_URL = "https://images.unsplash.com/photo-1628294895950-9805252327bc?auto=format&fit=crop&w=800&q=80";
  // =========================================================================

  // 1. HOME VIEW (HUB)
  const HomeView = () => (
    <div className="flex flex-col h-full bg-zinc-900 text-zinc-100">
      
      {/* Combined Hero & Slogan Section */}
      <div className="relative flex flex-col items-center justify-center pt-12 pb-10 px-6 border-b-4 border-red-700 min-h-[420px] overflow-hidden shadow-2xl">
        
        {/* Botón de Idioma Principal Flotante */}
        <div className="absolute top-4 right-4 z-40 flex bg-zinc-950/80 backdrop-blur-md border border-zinc-700 rounded-full overflow-hidden shadow-xl">
          <button onClick={() => setLang('en')} className={`px-3 py-1.5 text-xs font-black tracking-widest transition ${lang === 'en' ? 'bg-red-700 text-white' : 'text-zinc-500 hover:text-white'}`}>EN</button>
          <button onClick={() => setLang('es')} className={`px-3 py-1.5 text-xs font-black tracking-widest transition ${lang === 'es' ? 'bg-amber-600 text-zinc-900' : 'text-zinc-500 hover:text-white'}`}>ES</button>
        </div>

        {/* --- AQUI ESTÁ LA LÓGICA DEL VIDEO VS FOTO CORREGIDA --- */}
        {USAR_VIDEO_DE_FONDO && !videoError ? (
          <video 
            src={VIDEO_URL}
            poster={FOTO_DE_FONDO_URL} 
            autoPlay 
            loop 
            muted 
            playsInline 
            onError={() => setVideoError(true)} // Si el video falla, activa el error y muestra la foto
            className="absolute inset-0 w-full h-full object-cover opacity-60"
          />
        ) : (
          <img 
            src={FOTO_DE_FONDO_URL}
            alt="Slow Smoked BBQ" 
            className="absolute inset-0 w-full h-full object-cover opacity-50"
          />
        )}
        {/* --------------------------------------------- */}

        <div className="absolute inset-0 bg-gradient-to-b from-zinc-950/80 via-zinc-900/60 to-zinc-950/90 pointer-events-none"></div>
        
        {/* Content Container */}
        <div className="relative z-10 flex flex-col items-center w-full">
          
          <div className="bg-white rounded-full p-4 w-44 h-44 flex flex-col items-center justify-center border-4 border-zinc-900 shadow-[0_0_20px_rgba(0,0,0,0.8)] transform hover:scale-105 transition duration-300 mb-8 mt-4">
            <div className="absolute top-6 right-2 text-red-600 flex flex-col items-center rotate-12">
              <Star fill="currentColor" size={16} />
              <span className="text-[6px] font-black -mt-1 tracking-tighter">ESTD</span>
              <span className="text-[6px] font-black -mt-1 tracking-tighter">2018</span>
            </div>
            
            <h1 className="text-4xl font-extrabold text-zinc-900 leading-none -rotate-6" style={{ fontFamily: 'cursive' }}>Big</h1>
            <h1 className="text-4xl font-extrabold text-zinc-900 leading-none -rotate-6 -mt-2" style={{ fontFamily: 'cursive' }}>Nick's</h1>
            <p className="text-red-700 font-black tracking-[0.15em] text-[9px] mt-2 border-t-2 border-zinc-900 pt-1">BARBECUE</p>
          </div>

          <div className="text-center">
            <h2 className="text-4xl font-black text-white uppercase tracking-wider leading-tight drop-shadow-lg">
              {t[lang].slogan1}<br/>
              <span className="text-red-500">{t[lang].slogan2}</span>
            </h2>
            
            <div className="inline-flex items-center justify-center gap-2 mt-5 bg-zinc-950/60 py-1.5 px-4 rounded-full border border-zinc-700/50 backdrop-blur-sm shadow-xl">
              <Flame size={14} className="text-amber-500" />
              <p className="text-zinc-200 text-[10px] font-black tracking-[0.2em] uppercase drop-shadow">
                {t[lang].tagline}
              </p>
              <Flame size={14} className="text-amber-500" />
            </div>
          </div>

        </div>
      </div>

      <div className="flex-1 px-5 pt-8 pb-12 flex flex-col gap-4 bg-[url('https://www.transparenttextures.com/patterns/stardust.png')]">
        
        <button onClick={() => setCurrentView('menu')} className="w-full bg-red-700 text-white p-5 shadow-lg flex items-center justify-between hover:bg-red-800 transition active:scale-95 border-l-4 border-red-400 group">
          <div className="flex items-center gap-4">
            <Utensils size={28} className="text-red-300 group-hover:animate-pulse" />
            <span className="text-xl font-black uppercase tracking-wider">{t[lang].ourMenu}</span>
          </div>
          <ChevronRight size={24} className="text-white/70" />
        </button>

        <button onClick={() => setCurrentView('about')} className="w-full bg-zinc-800 text-zinc-100 p-5 shadow-lg flex items-center justify-between hover:bg-zinc-700 transition active:scale-95 border-l-4 border-zinc-500 group">
          <div className="flex items-center gap-4">
            <Flame size={28} className="text-zinc-400 group-hover:text-red-400 transition" />
            <span className="text-xl font-bold uppercase tracking-wider">{t[lang].ourStory}</span>
          </div>
          <ChevronRight size={24} className="text-zinc-500" />
        </button>

        <button onClick={() => setCurrentView('catering')} className="w-full bg-zinc-800 text-zinc-100 p-5 shadow-lg flex items-center justify-between hover:bg-zinc-700 transition active:scale-95 border-l-4 border-amber-600">
          <div className="flex items-center gap-4">
            <Truck size={28} className="text-amber-500" />
            <span className="text-xl font-bold uppercase tracking-wider">{t[lang].catering}</span>
          </div>
          <ChevronRight size={24} className="text-zinc-500" />
        </button>

        <button onClick={() => setCurrentView('social')} className="w-full bg-zinc-800 text-zinc-100 p-5 shadow-lg flex items-center justify-between hover:bg-zinc-700 transition active:scale-95 border-l-4 border-blue-500">
          <div className="flex items-center gap-4">
            <MapPin size={28} className="text-blue-400" />
            <span className="text-xl font-bold uppercase tracking-wider">{t[lang].locations}</span>
          </div>
          <ChevronRight size={24} className="text-zinc-500" />
        </button>
      </div>
    </div>
  );

  // 2. ABOUT VIEW
  const AboutView = () => (
    <div className="flex flex-col h-full bg-zinc-900 text-zinc-200 pb-12">
      <Header title={t[lang].ourStory} onBack={goHome} />
      <div className="overflow-y-auto">
        <img 
          src="https://images.unsplash.com/photo-1525648199074-cee30ba79a4a?auto=format&fit=crop&q=80&w=800" 
          alt="Restaurant Interior" 
          className="w-full h-56 object-cover border-b-4 border-red-700"
        />
        <div className="p-6 space-y-6">
          <SectionTitle>{t[lang].aboutTitle}</SectionTitle>
          <p className="leading-relaxed text-zinc-300">
            {t[lang].about1} <strong className="text-white">Big Nick's BBQ</strong> {t[lang].about1b}
          </p>
          <p className="leading-relaxed text-zinc-300">
            {t[lang].about2} <strong className="text-white">2022</strong>{t[lang].about2b} <strong className="text-white">Fort Myers, Florida</strong>{t[lang].about2c}
          </p>
          
          <div className="bg-red-900/30 border-l-4 border-red-600 p-5 shadow-inner">
            <p className="text-red-200 font-bold uppercase tracking-wide">
              {t[lang].aboutNew} <span className="text-white">Cape Coral, Florida</span>.
            </p>
          </div>

          <SectionTitle>{t[lang].qualityTitle}</SectionTitle>
          <p className="leading-relaxed text-zinc-300">
            {t[lang].qualityText}
          </p>
        </div>
      </div>
    </div>
  );

  // 3. MENU VIEW
  const MenuView = () => (
    <div className="flex flex-col h-full bg-zinc-950 text-zinc-100 pb-12">
      <Header title={t[lang].ourMenu} onBack={goHome} />

      <div className="px-3 py-6 overflow-y-auto">
        <p className="text-xs text-center text-zinc-500 mb-6 font-bold tracking-widest uppercase">{t[lang].pricesChange}</p>
        
        {menuData.map((section, idx) => (
          <div key={idx} className="mb-10 border-2 border-zinc-800 bg-zinc-900 shadow-2xl">
            <div className="relative h-48 w-full border-b-2 border-red-700 bg-zinc-800">
               <img 
                 src={section.image} 
                 alt={section.category[lang]} 
                 className="absolute inset-0 w-full h-full object-cover"
               />
               <div className="absolute inset-0 bg-gradient-to-t from-zinc-900/80 to-transparent"></div>
            </div>

            <div className="bg-red-700 text-white px-4 py-3 relative border-b border-red-900 shadow-inner">
              <h3 className="font-black text-xl uppercase tracking-wider">{section.category[lang]}</h3>
              {section.subtitle && <p className="text-red-200 text-xs font-bold uppercase tracking-widest mt-1 leading-snug opacity-90">{section.subtitle[lang]}</p>}
            </div>

            {section.columns && (
              <div className="flex justify-end gap-3 px-3 py-2 bg-zinc-950/80 border-b border-zinc-800">
                {section.columns[lang].map((col, cIdx) => (
                  <div key={cIdx} className="w-20 text-right text-[10px] font-black text-zinc-400 uppercase tracking-widest leading-tight whitespace-pre-line">
                    {col.replace(' [', '\n[')}
                  </div>
                ))}
              </div>
            )}
            
            <div className="divide-y divide-zinc-800/80 p-2">
              {section.items.map((item, itemIdx) => (
                <div 
                  key={itemIdx} 
                  onClick={() => setSelectedItem({ 
                    ...item, 
                    displayImage: item.image ? item.image : section.image, 
                    columns: section.columns 
                  })}
                  className="px-2 py-4 flex justify-between items-start hover:bg-zinc-800/60 transition group cursor-pointer"
                >
                  <div className="flex-1 pr-4">
                    <span className="font-black text-zinc-200 leading-snug uppercase block group-hover:text-white transition">{item.name[lang]}</span>
                    {item.desc && <span className="text-sm text-zinc-400 mt-1.5 font-medium leading-snug block normal-case">{item.desc[lang]}</span>}
                  </div>
                  <div className="flex gap-3 shrink-0 items-start mt-0.5">
                    {item.prices.map((price, pIdx) => (
                      <span key={pIdx} className="w-20 text-right font-black text-red-500">{price}</span>
                    ))}
                  </div>
                </div>
              ))}
            </div>
          </div>
        ))}

        <div className="mt-8 mb-8 px-2 space-y-4">
          <div className="w-full h-px bg-zinc-800 mb-6"></div>
          <h3 className="text-center font-black uppercase tracking-widest text-zinc-400 mb-2">{t[lang].readyToOrder}</h3>
          
          <div className="flex flex-col gap-3">
            <a href="https://www.bignicksbbq.com" target="_blank" rel="noopener noreferrer" className="w-full bg-red-700 text-white py-4 px-4 font-black uppercase tracking-wider text-sm flex items-center justify-center gap-2 hover:bg-red-600 transition shadow-lg border border-red-600">
              <ShoppingBag size={20} />
              {t[lang].orderToastFt}
            </a>
            <a href="https://www.bignicksbbq.com" target="_blank" rel="noopener noreferrer" className="w-full bg-amber-600 text-zinc-950 py-4 px-4 font-black uppercase tracking-wider text-sm flex items-center justify-center gap-2 hover:bg-amber-500 transition shadow-lg border border-amber-500">
              <ShoppingBag size={20} />
              {t[lang].orderToastCc}
            </a>
            <a href="tel:2392042498" className="w-full bg-transparent border-2 border-zinc-700 text-zinc-300 py-4 font-black uppercase tracking-widest flex items-center justify-center gap-2 hover:bg-zinc-800 transition mt-2">
              <Phone size={20} />
              {t[lang].questions}
            </a>
          </div>
        </div>
      </div>

      {/* Item Modal (Ventana Flotante) */}
      {selectedItem && (
        <div className="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/80 backdrop-blur-sm" onClick={() => setSelectedItem(null)}>
          <div className="bg-zinc-900 border border-zinc-700 w-full max-w-sm overflow-hidden shadow-2xl relative animate-in fade-in zoom-in duration-200" onClick={e => e.stopPropagation()}>
            <button 
              onClick={() => setSelectedItem(null)} 
              className="absolute top-3 right-3 z-20 bg-black/60 p-1.5 rounded-full text-white hover:bg-red-600 transition"
            >
              <X size={20} />
            </button>
            
            <div className="h-56 w-full relative border-b-2 border-red-700">
              <img 
                src={selectedItem.displayImage} 
                alt={selectedItem.name[lang]} 
                className="w-full h-full object-cover" 
              />
              <div className="absolute inset-0 bg-gradient-to-t from-zinc-900 via-zinc-900/40 to-transparent"></div>
            </div>
            
            <div className="p-6 relative -mt-8 z-10">
              <h3 className="text-2xl font-black text-white uppercase tracking-wider mb-2 leading-tight drop-shadow-md">
                {selectedItem.name[lang]}
              </h3>
              
              {selectedItem.desc && (
                <p className="text-zinc-300 text-sm mb-6 leading-relaxed font-medium">
                  {selectedItem.desc[lang]}
                </p>
              )}

              <div className="space-y-3 mb-6">
                {selectedItem.prices.map((price, idx) => {
                  let label = selectedItem.columns ? selectedItem.columns[lang][idx] : 'Price / Precio';
                  label = label.replace('[', '').replace(']', ''); 
                  
                  return (
                    <div key={idx} className="flex justify-between items-center bg-zinc-950 p-3 border border-zinc-800">
                      <span className="text-zinc-500 font-bold uppercase tracking-widest text-xs pr-4 whitespace-pre-line">
                        {label}
                      </span>
                      <span className="text-red-500 font-black text-xl">{price}</span>
                    </div>
                  );
                })}
              </div>

              <button 
                onClick={() => setSelectedItem(null)} 
                className="w-full bg-zinc-800 text-white py-3 font-black uppercase tracking-widest border border-zinc-700 hover:bg-zinc-700 transition"
              >
                {t[lang].backToMenu}
              </button>
            </div>
          </div>
        </div>
      )}
    </div>
  );

  // 4. CATERING VIEW
  const CateringView = () => (
    <div className="flex flex-col h-full bg-zinc-900 text-zinc-100 pb-12">
      <Header title={t[lang].catering} onBack={goHome} />
      <div className="overflow-y-auto">
        <img 
          src="https://images.unsplash.com/photo-1600891964092-4316c288032e?auto=format&fit=crop&w=800&q=80" 
          alt="BBQ Platter" 
          className="w-full h-64 object-cover border-b-4 border-amber-600"
        />
        <div className="p-6">
          <h2 className="text-3xl font-black text-white mb-2 uppercase tracking-tight">{t[lang].caterTitle}</h2>
          <div className="w-16 h-2 bg-amber-600 mb-6"></div>
          
          <p className="text-lg text-zinc-300 leading-relaxed mb-8 font-medium">
            {t[lang].caterDesc}
          </p>
          
          <div className="space-y-6 mb-10">
            <div className="flex items-start gap-4 bg-zinc-800 p-4 border-l-4 border-red-600">
              <Truck size={28} className="text-red-500 flex-shrink-0" />
              <div>
                <strong className="block text-white uppercase font-bold tracking-wider mb-1">{t[lang].fullService}</strong>
                <span className="text-zinc-400 text-sm">{t[lang].fullServiceDesc}</span>
              </div>
            </div>
            <div className="flex items-start gap-4 bg-zinc-800 p-4 border-l-4 border-amber-500">
              <Clock size={28} className="text-amber-500 flex-shrink-0" />
              <div>
                <strong className="block text-white uppercase font-bold tracking-wider mb-1">{t[lang].fastResponse}</strong>
                <span className="text-zinc-400 text-sm">{t[lang].fastResponseDesc}</span>
              </div>
            </div>
          </div>

          <div className="bg-zinc-950 p-6 border border-zinc-800 text-center relative overflow-hidden">
            <div className="absolute inset-0 opacity-10" style={{ backgroundImage: 'repeating-linear-gradient(90deg, transparent, transparent 10px, rgba(255,255,255,0.1) 10px, rgba(255,255,255,0.1) 20px)' }}></div>
            
            <p className="text-zinc-300 font-bold uppercase tracking-widest mb-4 relative z-10">{t[lang].readyToOrder}</p>
            <a href="tel:2392042498" className="relative z-10 inline-flex items-center justify-center w-full bg-red-700 text-white py-4 px-6 font-black uppercase tracking-wider gap-2 hover:bg-red-600 transition shadow-lg mb-3">
              <Phone size={24} />
              (239) 204-2498
            </a>
            <p className="text-sm text-zinc-500 mt-2 relative z-10">{t[lang].visitWeb}</p>
          </div>
        </div>
      </div>
    </div>
  );

  // 5. SOCIALS & CONTACT VIEW
  const SocialView = () => (
    <div className="flex flex-col h-full bg-zinc-900 text-zinc-100 pb-12">
      <Header title={t[lang].locations} onBack={goHome} />
      <div className="px-4 py-6 overflow-y-auto space-y-8">
        
        <div>
          <SectionTitle><MapPin className="inline mr-2 text-red-600" /> {t[lang].ourSpots}</SectionTitle>

          {/* Fort Myers */}
          <div className="bg-zinc-800 p-5 border-t-4 border-red-700 shadow-xl mb-6 relative overflow-hidden">
             <div className="absolute top-0 right-0 bg-red-700 text-white text-[10px] font-black px-3 py-1 uppercase tracking-widest">{t[lang].est}</div>
            <h4 className="font-black text-2xl text-white mb-2 uppercase">Fort Myers</h4>
            <p className="text-zinc-300 flex items-start gap-2 mb-4 text-sm font-medium">
              <MapPin size={18} className="mt-1 flex-shrink-0 text-red-500" />
              9211 Cypress Lake Drive<br/>Fort Myers, FL 33919
            </p>
            <div className="bg-zinc-950 p-4 text-sm border border-zinc-700 mb-5 font-mono">
              <p className="flex justify-between text-zinc-300 mb-1"><span>{t[lang].monSat}</span> <span className="text-white">11AM - 8PM*</span></p>
              <p className="flex justify-between text-zinc-300"><span>{t[lang].sun}</span> <span className="text-white">11AM - 7PM*</span></p>
              <p className="text-[10px] text-zinc-500 mt-2 italic">{t[lang].soldOut}</p>
            </div>
            <div className="flex gap-2">
               <a href="tel:2392042498" className="flex-1 bg-zinc-700 text-white py-3 font-bold uppercase tracking-wider text-xs flex items-center justify-center gap-2 hover:bg-zinc-600 transition">
                <Phone size={16} /> {t[lang].call}
              </a>
              <a href="https://maps.google.com/?q=9211+Cypress+Lake+Drive+Fort+Myers+FL" target="_blank" rel="noopener noreferrer" className="flex-1 bg-red-700 text-white py-3 font-bold uppercase tracking-wider text-xs flex items-center justify-center gap-2 hover:bg-red-600 transition">
                <MapPin size={16} /> {t[lang].map}
              </a>
            </div>
          </div>

          {/* Cape Coral */}
          <div className="bg-zinc-800 p-5 border-t-4 border-amber-500 shadow-xl relative overflow-hidden">
             <div className="absolute top-0 right-0 bg-amber-500 text-zinc-900 text-[10px] font-black px-3 py-1 uppercase tracking-widest animate-pulse">{t[lang].brandNew}</div>
            <h4 className="font-black text-2xl text-white mb-2 uppercase">Cape Coral</h4>
            <p className="text-zinc-300 flex items-start gap-2 mb-4 text-sm font-medium">
              <MapPin size={18} className="mt-1 flex-shrink-0 text-amber-500" />
              4720 SE 9th Place<br/>Cape Coral, FL 33904
            </p>
            <div className="bg-zinc-950 p-4 text-sm border border-zinc-700 mb-5 font-mono">
               <p className="flex justify-between text-zinc-300 mb-1"><span>{t[lang].monSat}</span> <span className="text-white">11AM - 9PM*</span></p>
              <p className="flex justify-between text-zinc-300"><span>{t[lang].sun}</span> <span className="text-white">11AM - 8PM*</span></p>
               <p className="text-[10px] text-zinc-500 mt-2 italic">{t[lang].soldOut}</p>
            </div>
            <div className="flex gap-2">
               <a href="tel:2392042498" className="flex-1 bg-zinc-700 text-white py-3 font-bold uppercase tracking-wider text-xs flex items-center justify-center gap-2 hover:bg-zinc-600 transition">
                <Phone size={16} /> {t[lang].call}
              </a>
              <a href="https://maps.google.com/?q=4720+SE+9th+Place+Cape+Coral+FL" target="_blank" rel="noopener noreferrer" className="flex-1 bg-amber-600 text-white py-3 font-bold uppercase tracking-wider text-xs flex items-center justify-center gap-2 hover:bg-amber-500 transition">
                <MapPin size={16} /> {t[lang].map}
              </a>
            </div>
          </div>
        </div>

        {/* Social Media */}
        <div>
          <SectionTitle><Share2 className="inline mr-2 text-zinc-400" /> {t[lang].connect}</SectionTitle>
          <div className="space-y-3">
            <a href="https://instagram.com/bignicksqq" target="_blank" rel="noopener noreferrer" className="flex items-center gap-4 p-4 bg-zinc-800 border border-zinc-700 hover:border-zinc-500 transition group">
              <Instagram size={24} className="text-zinc-400 group-hover:text-pink-500 transition" />
              <div className="flex-1">
                <p className="font-bold text-white uppercase tracking-wider">@bignicksqq</p>
                <p className="text-xs text-zinc-400">{t[lang].mainInsta}</p>
              </div>
              <ExternalLink size={18} className="text-zinc-600" />
            </a>
            <a href="https://instagram.com/bignicksbbqfm" target="_blank" rel="noopener noreferrer" className="flex items-center gap-4 p-4 bg-zinc-800 border border-zinc-700 hover:border-zinc-500 transition group">
              <Instagram size={24} className="text-zinc-400 group-hover:text-pink-500 transition" />
              <div className="flex-1">
                <p className="font-bold text-white uppercase tracking-wider">@bignicksbbqfm</p>
                <p className="text-xs text-zinc-400">{t[lang].fmCc}</p>
              </div>
              <ExternalLink size={18} className="text-zinc-600" />
            </a>
            <a href="https://facebook.com/bignicksbbqfm" target="_blank" rel="noopener noreferrer" className="flex items-center gap-4 p-4 bg-zinc-800 border border-zinc-700 hover:border-zinc-500 transition group">
              <Facebook size={24} className="text-zinc-400 group-hover:text-blue-500 transition" />
              <div className="flex-1">
                <p className="font-bold text-white uppercase tracking-wider">Big Nick's BBQ</p>
                <p className="text-xs text-zinc-400">{t[lang].fbPage}</p>
              </div>
              <ExternalLink size={18} className="text-zinc-600" />
            </a>
            <a href="https://www.bignicksbbq.com" target="_blank" rel="noopener noreferrer" className="flex items-center gap-4 p-4 bg-zinc-800 border border-zinc-700 hover:border-zinc-500 transition group">
              <Globe size={24} className="text-zinc-400 group-hover:text-white transition" />
              <div className="flex-1">
                <p className="font-bold text-white uppercase tracking-wider">{t[lang].website}</p>
                <p className="text-xs text-zinc-400">bignicksbbq.com</p>
              </div>
              <ExternalLink size={18} className="text-zinc-600" />
            </a>
          </div>
        </div>

      </div>
    </div>
  );

  return (
    <div className="min-h-screen bg-black flex justify-center w-full font-sans">
      <div className="w-full max-w-md bg-zinc-950 shadow-2xl relative overflow-x-hidden border-x border-zinc-900 flex flex-col min-h-screen">
        <div className="flex-1 flex flex-col">
          {currentView === 'home' && <HomeView />}
          {currentView === 'about' && <AboutView />}
          {currentView === 'menu' && <MenuView />}
          {currentView === 'catering' && <CateringView />}
          {currentView === 'social' && <SocialView />}
        </div>
        
        {/* Legal Footer */}
        <div className="w-full bg-zinc-950 py-6 border-t border-zinc-900 flex justify-center items-center mt-auto">
          <p className="text-zinc-600 text-[10px] uppercase tracking-widest font-bold text-center">
            &copy; {new Date().getFullYear()} Big Nick's BBQ.<br />{t[lang].rights}
          </p>
        </div>
      </div>
    </div>
  );
}
