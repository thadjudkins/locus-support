---
title: Locus - Genome Viewer support
---

# Locus - Genome Viewer

Locus is a genome browser mobile viewer for iPhone and iPad. It shows the
hg19 (GRCh37) human genome with standard UCSC annotations and custom tracks
from a UCSC shared session, built for touch.

Locus is for research and education. It is not a medical device and must not
be used to diagnose, treat, or make clinical decisions. Locus is an
independent app and is not affiliated with or endorsed by UCSC.

## Contact support

[Open an issue](https://github.com/thadjudkins/locus-support/issues) describing what you were doing, what you
expected, and what happened instead. A screenshot helps. Email support is
coming soon.

The quickest way is **••• → About & Help → Contact support** in the app. It
fills in your app version, iOS version, and device model, and if Locus has
crashed recently it offers to attach the crash reports. Those reports describe
where the app failed. They contain no genomic data or personal information,
and they stay on your device unless you attach them.

## Getting started

- **Pan** by dragging sideways across the tracks. **Zoom** by pinching,
  double-tapping a track, or using the zoom buttons.
- **Search** for a gene (BRCA1), a transcript (NM_007294), a dbSNP ID
  (rs80357906), or coordinates such as `chr17:41,196,312-41,277,500`.
- **Tap a feature** to see its details, zoom to it, copy its position or DNA,
  or align it with BLAT.
- **Tap UCSC** to choose tracks, import a shared session, or switch between
  up to eight workspaces.

The in-app guide (**••• → About & Help → Using Locus**) covers everything,
including keyboard shortcuts on iPad.

## Common questions

**Why do I need a UCSC API key?**
Shared sessions and BLAT use UCSC services that require a key. Sign in to the
[UCSC Genome Browser](https://genome.ucsc.edu), choose **My Data → Track Hubs
→ Hub Development**, and tap **Generate API key**. Locus stores the key in
your device's Keychain and sends it only to UCSC.

**A track says it's unavailable.**
Locus loads data live from UCSC. Check your connection. Locus retries
automatically when you're back online, or you can tap **Try again**. UCSC
sometimes limits busy clients, so waiting a minute can help.

**Does Locus work offline?**
Regions you've already viewed are cached for up to seven days, so they can
still be shown offline. New regions need a connection.

**Which genome does Locus show?**
The hg19 (GRCh37) human reference assembly. Positions are one-based, like the
UCSC Genome Browser.

**How do I remove my data?**
**••• → About & Help → Erase app data** removes workspaces, recent searches,
cached tracks, crash reports, and your saved API key. Deleting the app alone
doesn't remove the Keychain items, so use Erase app data first.

## Privacy

Locus doesn't collect personal data, use analytics, or show ads. See the
[privacy policy](privacy.md).
