<template>
    <div>
        <!-- Hero Section -->
        <HeroSection />

        <!-- Método Section -->
        <MetodoSection />

        <!-- Vibe Coding Section -->
        <VibeCodingSection />

        <!-- Método Componentização Section -->
        <MetodoComponentizacaoSection />

        <!-- Possibilidades Section -->
        <PossibilidadesSection />

        <!-- Conteúdo do Curso Section -->
        <ConteudoCursoSection />

        <!-- Depoimentos Section -->
        <DepoimentosSection />

        <!-- Checkout Section -->
        <CheckoutSection />

        <FaqSection/>

        <!-- Footer Section -->
        <FooterSection />

        <!-- WhatsApp Button -->
        <WhatsAppButton />

    </div>
</template>

<script setup>
// Import explícito dos componentes
import HeroSection from '~/components/sections/HeroSection.vue'
import MetodoSection from '~/components/sections/MetodoSection.vue'
import VibeCodingSection from '~/components/sections/VibeCodingSection.vue'
import MetodoComponentizacaoSection from '~/components/sections/MetodoComponentizacaoSection.vue'
import PossibilidadesSection from '~/components/sections/PossibilidadesSection.vue'
import ConteudoCursoSection from '~/components/sections/ConteudoCursoSection.vue'
import DepoimentosSection from '~/components/sections/DepoimentosSection.vue'
import CheckoutSection from '~/components/sections/CheckoutSection.vue'
import FaqSection from '~/components/sections/FaqSection.vue'
import FooterSection from '~/components/sections/FooterSection.vue'
import WhatsAppButton from '~/components/ui/WhatsAppButton.vue'


// Configurações da página
useHead({
    title: 'Crie seus SaaS com IA - Plataforma No-Code',
    meta: [
        { name: 'description', content: 'Desenvolva aplicativos com Inteligência Artificial de forma segura, escalável com total controle sobre seu código' }
    ]
})
</script>