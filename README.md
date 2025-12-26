# Popkaari – Final Live Website (v4)

This build adds:
- Instagram Reels hover preview (optional; uses your own MP4/posters in /assets/)
- Auto WhatsApp confirmation UX (copy-to-clipboard + clear CTA)
- Analytics hooks (GA4 + Meta Pixel) with safe loading + event tracking
- Smart scarcity ("Only X packs left") with daily stable stock + stock-aware cart
- Lighthouse performance optimizations (content-visibility, lazy loading)

## What you must update
1) WhatsApp number:
   STORE.whatsappNumber = "9198XXXXXXXX"
2) Analytics IDs (optional):
   STORE.ga4MeasurementId = "G-..."
   STORE.metaPixelId = "1234567890"
3) Reels hover previews (optional):
   Edit REELS[] array and host posters/mp4s under /assets/ on your site or CDN.
