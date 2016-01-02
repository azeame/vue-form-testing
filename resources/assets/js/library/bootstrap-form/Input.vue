<template>
    <div>
        <div id="input-{{label}}" class="input-group form-input-{{type}}">
            <label for="label-{{label | lowercase}}">
                {{label}}
            </label>
            <input name="{{label | lowercase}}" class="form-control" type="{{type}}">
        </div>
    </div>
</template>

<script>
    export default {
        props:['label','type']
    }
</script>

