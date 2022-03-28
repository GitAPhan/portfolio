<template>
    <div class="projects">
        <h1>Projects:</h1>
        <project-card v-for="project in projects" :key="project.id" :project="project" />
    </div>
</template>

<script>
import ProjectCard from './ProjectCard.vue'
export default {
    components: { ProjectCard },
    name: 'project-section',
    data() {
        return {
            projects: [
                {
                    "id": 1,
                    "name": "project name",
                    "tech": ["tech", "used", "here"],
                    "description": "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem.",
                    "live_link": "http://live_link.com",
                    "github_link": "https://github.com/",
                    "screenshot": "image",
                }, {
                    "id": 2,
                    "name": "project name",
                    "tech": ["tech", "used", "here"],
                    "description": "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem.",
                    "live_link": "http://live_link.com",
                    "github_link": "https://github.com/",
                    "screenshot": "image",
                }, {
                    "id": 3,
                    "name": "project name",
                    "tech": ["tech", "used", "here"],
                    "description": "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem.",
                    "live_link": "http://live_link.com",
                    "github_link": "https://github.com/",
                    "screenshot": "image",
                }, {
                    "id": 4,
                    "name": "project name",
                    "tech": ["tech", "used", "here"],
                    "description": "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem.",
                    "live_link": "http://live_link.com",
                    "github_link": "https://github.com/",
                    "screenshot": "image",
                },
            ]
        }
    },
}
</script>

<style>
.projects {
    height: 100vh;
}
</style> 