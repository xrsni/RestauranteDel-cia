// scripts.js

// Animação de rolagem suave
document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Validação do formulário de contato
document.getElementById('contatoForm').addEventListener('submit', function(e) {
    e.preventDefault(); // Evita o envio padrão do formulário

    const nome = document.getElementById('nome').value;
    const email = document.getElementById('email').value;
    const mensagem = document.getElementById('mensagem').value;

    if (nome && email && mensagem) {
        alert(Obrigado, ${nome}! Sua mensagem foi enviada com sucesso.);
        // Aqui você pode adicionar código para enviar a mensagem para um servidor, se necessário
        this.reset(); // Limpa o formulário após o envio
    } else {
        alert('Por favor, preencha todos os campos.');
    }
});
