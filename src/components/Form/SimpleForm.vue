<template>
    <div class="simple-form">
        <h1>Simple Form</h1>
        <div>
            <label for="">Text Input</label>
            <input type="text" name="" id="">
        </div>
        <div>
            <label for="">Text Input</label>
            <input type="text" name="" id="">
        </div>
        <div>
            <label for="">Select box</label>
            <select>
                <option value="">Value 1</option>
                <option value="">Value 2</option>
                <option value="">Value 3</option>
            </select>
        </div>
        <div>
            <label for="">Radio</label>
            <input type="radio" name="" id="">A
            <input type="radio" name="" id="">B
            <input type="radio" name="" id="">C
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped> 
h1 {
    margin: 1rem 0;
}

.simple-form {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1rem;
    align-items: center;
}

label {
    margin: 0 10px 0 0;
}

input[type = text], select, input[type = radio] {
    width: 200px;
    padding: 10px;
    outline: none;
    border: 2px solid #f0d068;
    font-size: 1rem;
}

select {
    width: 225px;
}

input[type = radio] {
    width: 50px;
}

input:focus, select:focus {
    border: 2px solid #f1bd14;
}
</style>