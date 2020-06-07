<template>
    <footer class="footer">
        <div class="footer-inner">
            <ul>
                <li>
                    <a href="//twitter.com/takeuma0825"
                    target="_blank"
                    >
                    <font-awesome-icon :icon="['fab', 'twitter']"/>
                    Twitter</a>
                </li>
                <li>
                    <a href="//github.com/takeuma0825"
                    target="_blank"
                    >
                    <font-awesome-icon :icon="['fab', 'github']"/>
                    GitHub</a>
                </li>
                <li>
                    <a href="//note.com/takeuma_0825"
                    target="_blank"
                    >
                    <font-awesome-icon :icon="['fas', 'note']"/>
                    note</a>
                </li>
            </ul>
        </div>
    </footer>
</template>

<script>
import { fab } from '@fortawesome/free-brands-svg-icons'
import { fas } from '@fortawesome/free-solid-svg-icons'
export default {
    computed: {
        fab () {
            return fab
        },
        fas () {
            return fas
        }
    },
    methods: {
    }
}
</script>

<style lang="scss" scoped>

.footer {
    box-sizing: border-box;
    padding: 36px 24px ;
    background-color: $color-gray;
    line-height: 30px;

    ul {
        display: flex;

        li {
            &:not(:last-of-type) {
                &::after {
                    content: '|';
                    margin: 0 10px;
                }
            }
        }
    }
    .footer-inner {
        max-width: var(--max-width);
        margin: 0 auto;
    }
}
</style>