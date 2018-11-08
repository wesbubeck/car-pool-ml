<template>
    <div class="custInput">
        <el-input placeholder="Name" v-model="name"></el-input>
        <el-input placeholder="Address" v-model="address"></el-input>
        <el-button type="primary" icon="el-icon-search">Search</el-button>
    </div>
</template>

<script>

import { Button } from 'element-ui';
import { Input } from 'element-ui';

export default {
    name: 'CustomerInput',
    components: {
        ElInput: Input,
        ElButton: Button
    },
    data() {
        return {
        name: '',
        address: ''
        }
    }
}
</script>