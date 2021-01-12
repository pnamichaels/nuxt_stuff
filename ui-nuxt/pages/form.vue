//pages/form.vue 
<template>
    <form data-abide novalidate>
        <div class="grid-container">
            <div class="grid-x">
                <div class="cell small-12">
                    <label>Email (Required)
                        <input type="text" placeholder="hello@example.com" required pattern="email">
                        <span class="form-error" data-form-error-on="required">
                            Sorry, this field is required
                        </span>
                        <span class="form-error" data-form-error-on="patern">
                            Sorry, thats an invalid email.
                        </span>
                    </label>
                    <div data-abide-error class="alert callout" style="display: none;">
                        <p><i class="fi-alert"></i> there are errors in your form.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="grid-container">
            <div class="grid-x">
                //...
            </div>
        </div>
    </form>
</template>