<!--
Copyright 2019 DigitalOcean

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

<template>
    <div class="no-search">
        <div class="graphic" v-html="dnsSVG"></div>
        <h2>{{ i18n.templates.skeletons.noSearch.title }}</h2>
    </div>
</template>

<script>
    import i18n from "../../i18n"
    import dnsSVG from "../../../../build/svg/dns.svg"

    export default {
        name: "NoSearch",
        data() {
            return {
                i18n,
                dnsSVG,
            }
        },
    }
</script>
