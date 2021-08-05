<template>
<q-header class="shadow-custom">
    <q-toolbar style="height : 64px">
        <div class="col-md-4 gt-sm row items-center">
            <div class="col-md-2 text-center">
                <q-avatar style="height : 1.8em ; width:1.8em">
                    <img src="/img/logo_welcome_page.png">
                </q-avatar>
            </div>
            <div class="col-md-10">
                <img
              src="/img/cerebrum_text_red.png"
              style="width: 30%"
              class="lt-lg"
            />
            </div>
        </div>

    </q-toolbar>
</q-header>
</template>
<script>
export default {
    name : "basic-header",
    props : ["title"],
    components :{

    }
    data() {
        return :{

        }
    },

    methods: {
        
    },
    created() {
        
    },
}
</script>
