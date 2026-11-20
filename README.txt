# Teaching Profession E-Portfolio

A responsive, academic-style portfolio for Kryzto Josh M. Manahan. The page documents the community engagement activity, teacher interview, DepEd Division Office visit, teaching philosophy, and photo gallery.

## Files

- `index.html` — all portfolio sections and content
- `style.css` — colors, typography, layouts, and responsive styling
- `script.js` — mobile navigation menu
- `assets/` — organized images, video, and documents (see `assets/README.md`)

## Preview locally

1. Open `index.html` in a web browser.
2. Review the page on desktop and mobile sizes.
3. Check the interview Q&A summaries and reflection against the recording.

## Assets

The supplied media is organized under `assets/`:

- `assets/images/` — portfolio photos, including the Tisa Elementary School photos, interview photos, and DepEd crops
- `assets/videos/manahan-interview.mp4` — interview recording
- `assets/documents/certificate-of-appearance-manahan.pdf` — Certificate of Appearance
- `assets/documents/school-activity-reflection.docx` — full one-page community engagement reflection
- `assets/documents/narrative-report.docx` — full two-page DepEd Division Office visit report
- `assets/documents/philosophy-resume.docx` — one-page teaching philosophy resume
- `assets/originals/` — original source photos and a copy of the certificate

No temporary placeholder images are used. See `assets/README.md` for the full file map and sources.

## Image framing

The page uses fixed image frames with `object-fit: cover`, so photos are cropped to fit automatically. Several images use the `pos-top`, `pos-upper`, or `pos-lower` classes to keep faces and activity details visible. On small phones, the hero image keeps its natural aspect ratio so the school sign stays visible.

## Interview Q&A

The teacher profile was filled from `for interview/teacher info.txt`: Mrs. Judeth Gonzales, English Teacher at Lawaan National High School, with 30 years of service. The seven Q&A summaries and the personal interview reflection were filled from the interview notes in `assets1(about me).txt`. Review them against the recording before submitting.

## Interview video

The interview is embedded with a local `<video>` player at `assets/videos/manahan-interview.mp4`. The file is 1.29 GB, so compress it or upload it to a video host before publishing. If you use a video host, replace the `<video>` block with the host's embed iframe and check the sharing permissions.

## Publish

This is a standalone website, not a native Google Sites theme. You can publish it using a static website host such as GitHub Pages or Netlify, subject to your instructor accepting a standalone website link. If the requirement specifically says Google Sites, use this as a design reference and recreate the sections in Google Sites.

## Before submitting

- Check names, dates, spelling, and school details.
- Review the interview Q&A summaries and reflection against the recording.
- Make sure the teacher meets the 20-year service requirement.
- Confirm the interview video's sharing settings.
- All individuals pictured have confirmed their consent for these photos; recheck if any photo is replaced.
- Compress the interview video or host it externally.
- Confirm the submission platform and link with your instructor.
