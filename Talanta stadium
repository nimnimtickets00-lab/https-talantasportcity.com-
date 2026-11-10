<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Talanta Ticket — Bayern Munich vs Ajax</title>
<script src="https://cdn.tailwindcss.com"></script>
<style>
  body { font-family: ui-sans-serif, system-ui, -apple-system, sans-serif; }
  .countdown-num { font-variant-numeric: tabular-nums; }
  .modal-backdrop { backdrop-filter: blur(6px); }
</style>
</head>
<body class="bg-[#0b0f14] text-white">

<!-- HEADER -->
<header class="border-b border-white/10">
  <div class="max-w-6xl mx-auto px-6 py-5 flex items-center justify-between">
    <div>
      <div class="text-[10px] uppercase tracking-[0.3em] text-emerald-400">Raila Odinga International Stadium</div>
      <div class="text-lg font-bold tracking-tight">Talanta Sports City</div>
      <div class="text-xs text-white/50">Nairobi • Kenya</div>
    </div>
    <nav class="hidden md:flex gap-6 text-sm text-white/70">
      <a href="#packages" class="hover:text-white">Packages</a>
      <a href="#travel" class="hover:text-white">Travel</a>
      <a href="#how" class="hover:text-white">How it works</a>
    </nav>
  </div>
</header>

<!-- HERO / MATCH -->
<section class="relative overflow-hidden">
  <div class="absolute inset-0 bg-gradient-to-b from-emerald-900/30 via-transparent to-[#0b0f14]"></div>
  <div class="relative max-w-6xl mx-auto px-6 py-16 text-center">
    <div class="text-xs uppercase tracking-[0.4em] text-emerald-400">International Friendly</div>
    <h1 class="mt-4 text-4xl md:text-6xl font-black tracking-tight">
      Bayern Munich <span class="text-white/40 font-light">VS</span> Ajax
    </h1>
    <div class="mt-3 text-white/60">Tue, 5 Jan 2027, 19:00 · Raila Odinga International Stadium</div>

    <!-- Countdown -->
    <div id="hero-countdown" class="mt-8 flex justify-center gap-6 md:gap-10"></div>

    <button onclick="openEnquiry('Bayern Munich vs Ajax', 'General')" class="inline-block mt-10 bg-emerald-500 hover:bg-emerald-400 text-black font-bold px-8 py-3 rounded-full transition">
      Request tickets — from KSh 10,000
    </button>
  </div>
</section>

<!-- TICKET CATEGORIES -->
<section class="max-w-6xl mx-auto px-6 py-12">
  <h2 class="text-2xl font-bold mb-6">Ticket categories</h2>
  <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-4" id="tier-grid"></div>
</section>

<!-- OFFERS & PACKAGES -->
<section id="packages" class="max-w-6xl mx-auto px-6 py-12">
  <div class="mb-8">
    <h2 class="text-2xl font-bold">Offers & packages</h2>
    <p class="text-white/50 mt-1">Come together, pay less per seat</p>
  </div>
  <div class="grid sm:grid-cols-2 gap-6 max-w-3xl" id="package-grid"></div>
</section>

<!-- TRAVEL -->
<section id="travel" class="max-w-6xl mx-auto px-6 py-16">
  <h2 class="text-2xl font-bold mb-2">Travel offers</h2>
  <p class="text-white/50 mb-8">Stay & travel for match day</p>

  <h3 class="text-sm uppercase tracking-widest text-emerald-400 mb-4">Accommodation — per night</h3>
  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6" id="hotel-grid"></div>

  <h3 class="text-sm uppercase tracking-widest text-emerald-400 mt-12 mb-4">Airport pickup & drop-off</h3>
  <div class="grid md:grid-cols-2 gap-6">
    <div class="bg-white/5 border border-white/10 rounded-2xl p-6">
      <div class="font-bold">Airport pickup</div>
      <p class="text-sm text-white/60 mt-2">We meet you at the arrivals hall and drive you to your hotel or the stadium.</p>
      <ul class="mt-4 text-sm space-y-2">
        <li class="flex justify-between"><span>Wilson Airport · Langata</span><span class="text-emerald-400">KSh 7,500 / trip</span></li>
        <li class="flex justify-between"><span>JKIA · Embakasi</span><span class="text-emerald-400">KSh 9,500 / trip</span></li>
      </ul>
      <button onclick="openTransfer('pickup')" class="mt-4 w-full bg-emerald-500/10 border border-emerald-500/30 hover:bg-emerald-500/20 text-emerald-400 font-semibold py-2 rounded-lg text-sm transition">Request pickup</button>
    </div>
    <div class="bg-white/5 border border-white/10 rounded-2xl p-6">
      <div class="font-bold">Airport drop-off</div>
      <p class="text-sm text-white/60 mt-2">Comfortable transfer back to the airport after the final whistle.</p>
      <ul class="mt-4 text-sm space-y-2">
        <li class="flex justify-between"><span>Wilson Airport · Langata</span><span class="text-emerald-400">KSh 7,500 / trip</span></li>
        <li class="flex justify-between"><span>JKIA · Embakasi</span><span class="text-emerald-400">KSh 9,500 / trip</span></li>
      </ul>
      <button onclick="openTransfer('drop-off')" class="mt-4 w-full bg-emerald-500/10 border border-emerald-500/30 hover:bg-emerald-500/20 text-emerald-400 font-semibold py-2 rounded-lg text-sm transition">Request drop-off</button>
    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section id="how" class="max-w-6xl mx-auto px-6 py-16 border-t border-white/10">
  <h2 class="text-2xl font-bold mb-8">How it works</h2>
  <div class="grid md:grid-cols-3 gap-6">
    <div class="bg-white/5 border border-white/10 rounded-2xl p-6">
      <div class="text-emerald-400 font-mono text-sm">01</div>
      <div class="font-bold mt-2">Send your request</div>
      <p class="text-sm text-white/60 mt-1">Tell us which tickets and how many. No payment is taken online.</p>
    </div>
    <div class="bg-white/5 border border-white/10 rounded-2xl p-6">
      <div class="text-emerald-400 font-mono text-sm">02</div>
      <div class="font-bold mt-2">We confirm by phone</div>
      <p class="text-sm text-white/60 mt-1">Our team contacts you to confirm seats and arrange payment.</p>
    </div>
    <div class="bg-white/5 border border-white/10 rounded-2xl p-6">
      <div class="text-emerald-400 font-mono text-sm">03</div>
      <div class="font-bold mt-2">Receive your ticket</div>
      <p class="text-sm text-white/60 mt-1">Once payment is confirmed, your official ticket is issued.</p>
    </div>
  </div>
</section>

<footer class="border-t border-white/10 py-8 text-center text-xs text-white/40">
  Talanta Sports City — ticket enquiries only.
</footer>

<!-- MODAL -->
<div id="modal" class="fixed inset-0 hidden items-center justify-center z-50">
  <div class="absolute inset-0 bg-black/70 modal-backdrop" onclick="closeModal()"></div>
  <div class="relative bg-[#10161d] border border-white/10 rounded-2xl w-full max-w-md mx-4 p-6">
    <div class="flex items-start justify-between">
      <div>
        <div class="text-xs uppercase tracking-widest text-emerald-400" id="modal-eyebrow">Enquiry</div>
        <div class="text-lg font-bold mt-1" id="modal-title">—</div>
      </div>
      <button onclick="closeModal()" class="text-white/50 hover:text-white text-xl leading-none">×</button>
    </div>
    <div id="modal-body" class="mt-5 space-y-4"></div>
  </div>
</div>

<script>
// ---------- CONFIG ----------
const KICKOFF = '2027-01-05T19:00:00+03:00';

const TIERS = [
  { name: 'Regular', price: 'KSh 10,000', desc: 'Open stands, great atmosphere' },
  { name: 'Business', price: 'KSh 22,000', desc: 'Reserved seating with better views' },
  { name: 'VIP', price: 'KSh 35,000', desc: 'Covered seating, priority entry' },
  { name: 'VVIP', price: 'KSh 80,000', desc: 'Premium lounge, hospitality' },
];

const PACKAGES = [
  { name: 'Couple Package', price: 'KSh 65,000', perPerson: 'KSh 32,500 per person', desc: '2 seats together — perfect for a date at the match' },
  { name: 'Group Package', price: 'KSh 200,000', perPerson: 'KSh 20,000 per person', desc: '10 seats together for friends, family or teams' },
];

const HOTELS = [
  { name: 'Serena Hotel', price: 'KSh 27,000' },
  { name: 'Skynest Residences', price: 'KSh 18,000' },
  { name: 'Park Inn', price: 'KSh 17,900' },
  { name: 'National Hill Cottages', price: 'KSh 15,500' },
  { name: 'Villa Rosa', price: 'KSh 31,190' },
  { name: 'Sarova Stanley Hotel', price: 'KSh 21,600' },
];

// ---------- COUNTDOWN ----------
function renderCountdown(containerId, targetIso) {
  const el = document.getElementById(containerId);
  if (!el) return;
  const target = new Date(targetIso).getTime();
  function tick() {
    const diff = target - Date.now();
    if (diff <= 0) { el.innerHTML = '<span class="text-emerald-400 font-mono text-xl">Live</span>'; return; }
    const d = Math.floor(diff / 86400000);
    const h = Math.floor((diff % 86400000) / 3600000);
    const m = Math.floor((diff % 3600000) / 60000);
    const s = Math.floor((diff % 60000) / 1000);
    const parts = [
      { v: d, l: 'Days' }, { v: h, l: 'Hrs' }, { v: m, l: 'Min' }, { v: s, l: 'Sec' }
    ];
    el.innerHTML = parts.map(p => `
      <div class="text-center">
        <div class="countdown-num text-3xl md:text-4xl font-bold text-emerald-400">${String(p.v).padStart(2,'0')}</div>
        <div class="text-[10px] uppercase tracking-widest text-white/40 mt-1">${p.l}</div>
      </div>`).join('');
  }
  tick();
  setInterval(tick, 1000);
}
renderCountdown('hero-countdown', KICKOFF);

// ---------- TIERS ----------
document.getElementById('tier-grid').innerHTML = TIERS.map(t => `
  <div class="bg-white/5 border border-white/10 rounded-2xl p-5 flex flex-col hover:border-emerald-500/40 transition">
    <div class="font-bold">${t.name}</div>
    <div class="text-xl font-black text-emerald-400 mt-1">${t.price}</div>
    <div class="text-xs text-white/50 mt-1">Per person</div>
    <p class="text-sm text-white/60 mt-2 flex-1">${t.desc}</p>
    <button onclick="openEnquiry('${t.name}', 'Ticket')" class="mt-4 bg-emerald-500/10 border border-emerald-500/30 hover:bg-emerald-500/20 text-emerald-400 font-semibold py-2 rounded-lg text-sm transition">
      Request ${t.name}
    </button>
  </div>
`).join('');

// ---------- PACKAGES ----------
document.getElementById('package-grid').innerHTML = PACKAGES.map(p => `
  <div class="bg-white/5 border border-white
