# mmallaki

DevOps / SRE. I build and run small systems end to end — Linux, Docker, WordPress, CI — and I
write down the parts that are easy to forget, because a system whose reasoning lives only in
someone's head stops being maintainable the day that person is unavailable.

## What I am working on

**[mandegar-wp](https://github.com/mmallaki/mandegar-wp)** *(private)* — a WordPress block theme for
a working frame-maker's shop (`mandegarghab.ir`). Not a mockup: 20 CSS files whose number is their
position in the cascade, page content that lives in the database but arrives through replayable
migrations, a REST deploy endpoint that refuses downgrades, and verification gates that prove a
refactor changed no pixel. Documentation is bilingual (EN/FA) because the owner and I do not read
the same language comfortably.

**[project-standards](https://github.com/mmallaki/project-standards)** — the documentation skeleton
I put in every repository: two READMEs, a 60-line `AGENTS.md` map, a short handoff, an open-items
checklist with costs, and a decision log that keeps the rejected options. It ships with a scaffold
script and a checker that fails on a missing language, an unfilled placeholder, or a
credential-shaped string.

## Selected repositories

| repo | what it is |
|---|---|
| [project-standards](https://github.com/mmallaki/project-standards) | bilingual documentation skeleton + gate; used by everything below |
| [pastebin-service](https://github.com/mmallaki/pastebin-service) | FastAPI service, containerised, with a CI pipeline |
| [netswitch](https://github.com/mmallaki/netswitch) | network switching helper for a Linux desktop |
| [multi-docker](https://github.com/mmallaki/multi-docker) | multi-service Docker Compose setup |

## How I work

- **Measure, then claim.** A number with a command behind it, or "unknown" — never "production-ready".
- **One logical change, one commit.** A refactor and a visible change never travel together.
- **The irreversible step waits.** Deploy, merge, delete: a written decision first, an action after.
- **Facts live next to the code.** If a future session — mine or an agent's — needs chat history to
  continue, the repository is incomplete.

## فارسی

مهندس DevOps / SRE. سیستم‌های کوچک را از صفر تا تولید می‌برم — لینوکس، داکر، وردپرس، CI — و چیزهایی
را که راحت فراموش می‌شوند می‌نویسم. باور دارم اگر ادامه‌دادن یک پروژه به تاریخچهٔ یک مکالمه وابسته
باشد، آن پروژه ناتمام است: مستندات باید داخل مخزن باشند، دوزبانه، با عدد و دستور، نه با صفت.

دو نمونه: قالب وردپرس سایت یک کارگاه قاب‌سازی (خصوصی، با گیت‌های بررسی و استقرار از طریق endpoint)،
و `project-standards` — اسکلت مستنداتی که در هر مخزن می‌گذارم، همراه با اسکریپت ساخت و یک گیت که
نبودِ زبان دوم، جای‌خالی پرنشده، یا رشتهٔ شبیه رمز را رد می‌کند.
