<template>
    <v-card>
        <v-footer
        class="font-weight-medium pa-10"
        color="secondary"
        >
            <v-btn href="https://www.facebook.com/profile.php?id=61555754949326" depressed class="third--text secondary">
                <v-icon>mdi-facebook</v-icon>
            </v-btn> 
            
            <v-btn href="https://www.instagram.com/pavlymakram/" depressed class="third--text secondary">
                <v-icon>mdi-instagram</v-icon>
            </v-btn>
            <v-btn href="https://www.linkedin.com/in/pavly-makram-b99983221/" depressed class="third--text secondary">
                <v-icon>mdi-linkedin</v-icon>
            </v-btn>
            <v-spacer/>
            <p class="third--text">&copy; {{ new Date().getFullYear() }},  <strong>Online Cources</strong></p>
        </v-footer>
    </v-card>
</template>