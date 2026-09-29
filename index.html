import { useState } from 'react';
import brazilFlag from 'flag-icons/flags/4x3/br.svg';
import argentinaFlag from 'flag-icons/flags/4x3/ar.svg';
import chileFlag from 'flag-icons/flags/4x3/cl.svg';
import mexicoFlag from 'flag-icons/flags/4x3/mx.svg';
import colombiaFlag from 'flag-icons/flags/4x3/co.svg';
import boliviaFlag from 'flag-icons/flags/4x3/bo.svg';
import usaFlag from 'flag-icons/flags/4x3/us.svg';

type FestivalEvent = {
  title: string;
  subtitle?: string;
  kind: 'Obra' | 'Taller';
  venue: string;
  audience: string;
  times: string[];
  tag?: string;
};

type FestivalDay = {
  id: string;
  short: string;
  name: string;
  date: string;
  note?: string;
  events: FestivalEvent[];
};

const days: FestivalDay[] = [
  {
    id: 'domingo', short: 'DOM', name: 'Domingo', date: '04', note: 'Apertura del festival · Para toda la familia',
    events: [
      { title: 'Una familia como la tuya', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Todas las familias · Público general', times: ['20:00'], tag: 'Obra inaugural' },
    ],
  },
  {
    id: 'lunes', short: 'LUN', name: 'Lunes', date: '05',
    events: [
      { title: 'Cuentos Chilombianos', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Mayores de 15 años', times: ['10:30', '14:30'] },
      { title: 'Palabras Andantes', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Público general', times: ['18:00'] },
    ],
  },
  {
    id: 'martes', short: 'MAR', name: 'Martes', date: '06',
    events: [
      { title: 'Violeta de los Andes', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Público general', times: ['15:00'] },
      { title: 'Taller de pantomima y narración oral', kind: 'Taller', venue: 'Escuela de Artes Martín Rodríguez', audience: 'Niños y adultos', times: ['17:00'] },
      { title: 'Hot Line', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Mayores de 18 años', times: ['18:00'] },
    ],
  },
  {
    id: 'jueves', short: 'JUE', name: 'Jueves', date: '08',
    events: [
      { title: 'Zorro Gris Agente de Cobranza', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Niños y público general', times: ['10:30', '14:30'] },
      { title: 'Taller de pantomima y juego dramático', kind: 'Taller', venue: 'Escuela de Arte Artemisa', audience: 'Público general', times: ['16:00'] },
    ],
  },
  {
    id: 'viernes', short: 'VIE', name: 'Viernes', date: '09',
    events: [
      { title: 'Mimoxtasis', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Niños y público general', times: ['10:30', '14:30'] },
      { title: 'Tabú', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Mayores de 16 años', times: ['18:00'] },
      { title: 'Hamlet Nuestro de Cada Día', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Público general', times: ['20:00'] },
    ],
  },
  {
    id: 'sabado', short: 'SÁB', name: 'Sábado', date: '10', note: 'Cierre del festival',
    events: [
      { title: 'Ellas y Yo Mexicanas', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Público general', times: ['20:00'] },
      { title: 'Una familia como la tuya', kind: 'Obra', venue: 'Teatro Municipal', audience: 'Todas las familias · Público general', times: ['20:15'], tag: 'Cierre del festival' },
    ],
  },
];

const countries = [
  { flag: brazilFlag, name: 'Brasil' }, { flag: argentinaFlag, name: 'Argentina' },
  { flag: chileFlag, name: 'Chile' }, { flag: mexicoFlag, name: 'México' },
  { flag: colombiaFlag, name: 'Colombia' }, { flag: boliviaFlag, name: 'Bolivia' },
  { flag: usaFlag, name: 'Estados Unidos' },
] as const;

function ArrowIcon({ diagonal = false }: { diagonal?: boolean }) {
  return diagonal ? (
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round" aria-hidden="true">
      <path d="M5 19 19 5M8 5h11v11" />
    </svg>
  ) : (
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round" aria-hidden="true">
      <path d="M4 12h16m-7-7 7 7-7 7" />
    </svg>
  );
}

function PinIcon() {
  return (
    <svg viewBox="0 0 18 18" fill="none" stroke="currentColor" strokeWidth="1.7" strokeLinecap="round" strokeLinejoin="round" aria-hidden="true">
      <path d="M14.4 7.4c0 4-5.4 8.4-5.4 8.4S3.6 11.4 3.6 7.4a5.4 5.4 0 0 1 10.8 0Z" />
      <circle cx="9" cy="7.3" r="1.8" />
    </svg>
  );
}

function OlmedoMark({ className = '' }: { className?: string }) {
  return (
    <svg className={className} viewBox="0 0 104 132" fill="none" stroke="currentColor" strokeWidth="2.1" strokeLinecap="round" strokeLinejoin="round" aria-label="Logotipo de Organización El Negro Olmedo" role="img">
      {/* Caja superior con la palabra Organización */}
      <rect x="3" y="3" width="98" height="21" rx="2" strokeWidth="2.1" />
      <text x="52" y="17.6" textAnchor="middle" fill="currentColor" stroke="none" fontFamily="'DM Sans', -apple-system, BlinkMacSystemFont, sans-serif" fontSize="12.4" fontWeight="600" letterSpacing="0.1">Organización</text>

      {/* Escudo / blasón lateral derecho: ancho arriba, punta abajo a la izquierda */}
      <path d="M50 32 H95 V74 C95 94 82 111 52 127 C58 112 58 100 58 88 V32 Z" strokeWidth="2.1" />

      {/* Diamante interior del escudo */}
      <polygon points="73,46 80,55.5 73,65 66,55.5" strokeWidth="1.9" />

      {/* Letra 'n' con asta izquierda y serif superior izquierdo */}
      <path d="M11 82 V42 L7 38 L15 30 H24 C31 30 36 35 36 42 V82 H27 V49 C27 46 25 44 22 44 C19 44 17 46 17 49 V82 Z" strokeWidth="2.1" />

      {/* Letra 'ó': anillo ovalado con diamante-acento sobre el hombro derecho */}
      <ellipse cx="45" cy="80" rx="14.5" ry="19.5" strokeWidth="2.1" />
      <ellipse cx="45" cy="80" rx="6.2" ry="10.5" strokeWidth="1.9" />
      <polygon points="52,53 57.5,59 52,65 46.5,59" strokeWidth="1.8" />
    </svg>
  );
}

function MercedesLogo() {
  return (
    <div className="mercedes-logo" aria-label="Mercedes, ciudad de todos">
      <svg viewBox="0 0 112 76" fill="none" stroke="currentColor" strokeWidth="2.3" strokeLinecap="round" strokeLinejoin="round" aria-hidden="true">
        {/* Triángulo 1: vértice superior izquierdo, base inferior común */}
        <path d="M8 64 L38 12 A3 3 0 0 1 41 10 L102 64" />
        {/* Triángulo 2: vértice superior derecho, base inferior común */}
        <path d="M8 64 L71 10 A3 3 0 0 1 74 12 L104 64 Z" />
        {/* Base inferior común */}
        <path d="M8 64 H104" />
      </svg>
      <strong>mercedes</strong>
      <span>ciudad de todos</span>
    </div>
  );
}

function FreeEntryBadge() {
  return (
    <svg className="free-entry-badge" viewBox="0 0 130 130" role="img" aria-label="Entrada libre y gratuita">
      <defs>
        <linearGradient id="free-badge-grad" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stopColor="#cf3d8c" />
          <stop offset="48%" stopColor="#6765b4" />
          <stop offset="100%" stopColor="#25a3d8" />
        </linearGradient>
        <path id="badge-circle-path" d="M 65 17 A 48 48 0 1 1 64.9 17" fill="none" />
      </defs>
      <circle cx="65" cy="65" r="57" fill="url(#free-badge-grad)" />
      <text fill="#ffffff" fontFamily="'DM Sans', -apple-system, BlinkMacSystemFont, sans-serif" fontSize="8.3" fontWeight="800" letterSpacing="1.2">
        <textPath href="#badge-circle-path" startOffset="4%">
          • LIBRE Y GRATUITO • LIBRE Y GRATUITO
        </textPath>
      </text>
    </svg>
  );
}

function FestivalLogo({ footer = false }: { footer?: boolean }) {
  return (
    <div className={`festival-logo ${footer ? 'festival-logo--footer' : ''}`} aria-label="VI FITOV 2026, Beba Mayo">
      <div className="festival-logo__main"><span>VI</span><strong>FITOV</strong><span>2026</span></div>
      <span className="festival-logo__dedication">Beba Mayo</span>
    </div>
  );
}

export default function App() {
  const [selectedDay, setSelectedDay] = useState('todos');
  const [menuOpen, setMenuOpen] = useState(false);
  const visibleDays = selectedDay === 'todos' ? days : days.filter((day) => day.id === selectedDay);
  const visibleEvents = visibleDays.reduce((total, day) => total + day.events.length, 0);

  return (
    <div className="site-shell" id="inicio">
      <header className="site-header">
        <a className="organizer-brand" href="#inicio" aria-label="El Negro Olmedo, volver al inicio" onClick={() => setMenuOpen(false)}>
          <OlmedoMark className="organizer-brand__mark" />
          <span>EL NEGRO<br />OLMEDO</span>
        </a>

        <a className="header-festival-logo" href="#inicio" aria-label="FITOV 2026, volver al inicio" onClick={() => setMenuOpen(false)}>
          <FestivalLogo />
        </a>

        <nav className={`site-nav ${menuOpen ? 'site-nav--open' : ''}`} aria-label="Navegación principal">
          <a href="#paises" onClick={() => setMenuOpen(false)}>El encuentro</a>
          <a href="#programacion" onClick={() => setMenuOpen(false)}>Programación</a>
          <a href="#organizacion" onClick={() => setMenuOpen(false)}>Organización</a>
          <a className="site-nav__cta" href="#programacion" onClick={() => setMenuOpen(false)}>Ver agenda <ArrowIcon diagonal /></a>
        </nav>

        <button className="menu-toggle" type="button" aria-label={menuOpen ? 'Cerrar menú' : 'Abrir menú'} aria-expanded={menuOpen} onClick={() => setMenuOpen((open) => !open)}>
          <span className={menuOpen ? 'menu-toggle__line menu-toggle__line--top-open' : 'menu-toggle__line'} />
          <span className={menuOpen ? 'menu-toggle__line menu-toggle__line--bottom-open' : 'menu-toggle__line'} />
        </button>
      </header>

      <main>
        <section className="hero" aria-labelledby="hero-title">
          <img
            className="hero__art"
            src="https://noticiasmercedinas.com/site/wp-content/uploads/2026/09/IMG-20260923-WA0022.jpg"
            alt="Afiche oficial del VI FITOV 2026 «Beba Mayo»: el hombre del sombrero bombín junto a la mano pintada de colores"
            onError={(e) => {
              const img = e.currentTarget;
              if (img.dataset.fallback !== '1') {
                img.dataset.fallback = '1';
                img.src = '/images/fitov-hero-v2.jpg';
              }
            }}
          />
          <div className="hero__shade" />
          <div className="hero__content">
            <p className="hero__eyebrow">EL NEGRO OLMEDO PRESENTA <span>/</span> VI EDICIÓN · BEBA MAYO</p>
            <div className="hero__wordmark" aria-label="FITOV 2026">FITOV<span>2026</span></div>
            <h1 id="hero-title">Festival Internacional<br />de Teatro en Mercedes</h1>
            <p className="hero__intro">Del 4 al 10 de octubre, el teatro nos encuentra en Mercedes.</p>
            <div className="hero__actions">
              <a className="button-primary" href="#programacion">Explorar programación <ArrowIcon diagonal /></a>
              <a className="hero__text-link" href="#paises">Conocé el encuentro <ArrowIcon /></a>
            </div>
          </div>
          <div className="hero__bottom-line" aria-hidden="true"><span /><span /><span /></div>
        </section>

        <section className="countries-section" id="paises" aria-labelledby="countries-title">
          <div className="countries-section__inner page-width">
            <div className="countries-section__heading">
              <p className="section-label section-label--dark">UN ENCUENTRO SIN FRONTERAS</p>
              <h2 id="countries-title">Siete países.<br /><em>Un mismo escenario.</em></h2>
            </div>
            <div className="countries-grid">
              {countries.map((country) => (
                <div className="country" key={country.name}>
                  <img className="country-flag" src={country.flag} alt={`Bandera de ${country.name}`} />
                  <span>{country.name}</span>
                </div>
              ))}
            </div>
          </div>
        </section>

        <section className="program-section" id="programacion" aria-labelledby="program-title">
          <div className="page-width">
            <div className="program-intro">
              <div>
                <p className="section-label">PROGRAMA OFICIAL / OCTUBRE 2026</p>
                <h2 id="program-title">La semana<br /><em>en escena.</em></h2>
              </div>
              <div className="program-intro__aside">
                <p>Obras, talleres y encuentros para vivir el teatro de cerca. Elegí un día o recorré la agenda completa.</p>
                <button className="print-link" type="button" onClick={() => window.print()}>Imprimir programa <ArrowIcon diagonal /></button>
              </div>
            </div>

            <div className="program-layout">
              <aside className="day-filter" aria-label="Filtrar programación por día">
                <p className="day-filter__label">EXPLORÁ POR DÍA</p>
                <button className={`day-filter__button ${selectedDay === 'todos' ? 'day-filter__button--active' : ''}`} type="button" aria-pressed={selectedDay === 'todos'} onClick={() => setSelectedDay('todos')}>
                  <span>Todos los días</span><ArrowIcon diagonal />
                </button>
                {days.map((day) => (
                  <button className={`day-filter__button ${selectedDay === day.id ? 'day-filter__button--active' : ''}`} type="button" aria-pressed={selectedDay === day.id} key={day.id} onClick={() => setSelectedDay(day.id)}>
                    <span>{day.name} <small>{day.date}</small></span><ArrowIcon diagonal />
                  </button>
                ))}
              </aside>

              <div className="schedule" aria-live="polite">
                <div className="schedule__topline"><span>{selectedDay === 'todos' ? 'AGENDA COMPLETA' : 'AGENDA DEL DÍA'}</span><span>{visibleEvents} {visibleEvents === 1 ? 'ACTIVIDAD' : 'ACTIVIDADES'}</span></div>
                <div className="schedule__groups" key={selectedDay}>
                  {visibleDays.map((day) => (
                    <section className="schedule-day" key={day.id} aria-labelledby={`day-${day.id}`}>
                      <div className="schedule-day__header">
                        <div className="date-block"><span>{day.short}</span><strong>{day.date}</strong></div>
                        <div className="schedule-day__heading"><h3 id={`day-${day.id}`}>{day.name} <span>de octubre</span></h3>{day.note && <p>{day.note}</p>}</div>
                      </div>
                      <div className="schedule-day__events">
                        {day.events.map((event) => (
                          <article className="event-row" key={`${day.id}-${event.title}`}>
                            <div className="event-row__times" aria-label={event.times.length > 1 ? 'Horarios' : 'Horario'}>
                              {event.times.map((time) => <span className="time-block" key={time}>{time}<small> h</small></span>)}
                            </div>
                            <div className="event-row__main">
                              <div className="event-row__badges">
                                <span className={`event-row__kind ${event.kind === 'Taller' ? 'event-row__kind--workshop' : ''}`}>{event.kind}</span>
                                {event.tag && <span className="event-row__tag">{event.tag}</span>}
                              </div>
                              <h4>{event.title}</h4>
                              {event.subtitle && <p className="event-row__subtitle">{event.subtitle}</p>}
                              <p>Público: {event.audience.toLowerCase()}</p>
                            </div>
                            <div className="event-row__venue"><span className="venue-block"><PinIcon />{event.venue}</span></div>
                          </article>
                        ))}
                      </div>
                    </section>
                  ))}
                </div>
              </div>
            </div>
          </div>
        </section>

        <section className="organization-section" id="organizacion" aria-labelledby="organization-title">
          <div className="page-width organization-section__inner">
            <div className="organization-section__copy">
              <p className="section-label section-label--dark">VI FITOV 2026 / BEBA MAYO</p>
              <h2 id="organization-title">El teatro<br />nos encuentra<span>.</span></h2>
              <p>Una semana de historias para compartir en Mercedes. Entrada libre y gratuita.</p>
            </div>
            <div className="organization-section__logos">
              <FreeEntryBadge />
              <div className="organization-section__partners">
                <div className="partner">
                  <span>Organiza</span>
                  <div className="partner__olmedo"><OlmedoMark /></div>
                </div>
                <div className="partner">
                  <span>Acompaña</span>
                  <MercedesLogo />
                </div>
              </div>
            </div>
          </div>
        </section>
      </main>

      <footer className="site-footer">
        <div className="page-width site-footer__inner">
          <a href="#inicio" aria-label="Volver al inicio"><FestivalLogo footer /></a>
          <p>Festival Internacional de Teatro en Mercedes<br />4 al 10 de octubre de 2026</p>
          <a className="site-footer__top" href="#inicio">Volver arriba <ArrowIcon diagonal /></a>
        </div>
      </footer>
    </div>
  );
}
