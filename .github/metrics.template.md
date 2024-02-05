### 👋 Hi, I'm {{ LOGIN }}

---

![ichirei](https://github.com/ichirei/ichirei/assets/83379604/e87d44b3-8db3-491b-b0b5-a92df9d9169b)

<%- await embed(`base`, { base: "header, activity, community, repositories, metadata" }) %>



<details>
    <summary><b>📰 Recent activity</b></summary>
    <%- await embed(`activity`, { activity: true }) %>
</details>

<details>
    <summary><b>🗓️ My Calendar</b></summary>
    <%- await embed(`isocalendar`, { isocalendar: true, isocalendar_duration: "full-year" }) %>
</details>

<details>
    <summary><b>🔥 My Streak</b></summary>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=ichirei&theme=dark" alt="streak" />
</details>

<details>
    <summary><b>🟣 Used Languages</b></summary>
    <img src="https://github-readme-stats.vercel.app/api/wakatime?username=ichirei&border_radius=30&hide_border=true&bg_color=313849&title_color=667EBD&text_color=B1BACD" alt="wakatime" />
</details>

<details>
    <summary><b>🏅 Achievements</b></summary>
    <%- await embed(`achievements`, { achievements: true, achievements_display: "compact" }) %>
</details>
