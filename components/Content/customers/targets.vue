<template>
    <div>
        <v-toolbar color="transparent" class="topToolbar">
            <v-row>
                <v-col cols="9">
                    <v-toolbar-title class="toolbarTitle">Targets</v-toolbar-title>
                </v-col>
                <v-col cols="1">
                    <addtarget />
                </v-col>
            </v-row>
        </v-toolbar>
        <v-table fixed-header class="customerTable">
            <thead>
                <tr>
                    <th class="text-left">
                        Name
                    </th>
                    <th class="text-left">
                        Job Title
                    </th>
                    <th class="text-left">
                        Email
                    </th>
                    <th class="text-left">
                        Phone
                    </th>
                    <th class="text-left">
                        Date Created
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
            </tbody>
        </v-table>
    </div>
</template>

<script>
import addtarget from './Add/add-target.vue'

export default {
    components: { addtarget }
}
</script>

<script setup>
    useHead({
        title: 'Targets'
    })
</script>