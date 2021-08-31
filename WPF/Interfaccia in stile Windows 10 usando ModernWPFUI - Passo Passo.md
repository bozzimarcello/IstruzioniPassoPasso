# Interfaccia in stile Windows 10 usando ModernWPFUI - Passo Passo
1. Creare un progetto "Applicazione WPF", target NET 5
1. Aprire Strumenti->Gestione pacchetti NuGet->Gestisci i pacchetti NuGet per la soluzione
1. Vai sulla tab "Sfoglia" e cerca "ModernWpfUI", seleziona nell'elenco "ModernWpfUI di Yimeng Wu", poi nele proprietà a destra spunta il check a fianco di "Progetto", infine clic su "Installa"
1. Nel readme.txt che compare dopo l'installazione ci sono le istruzioni da seguire, usale per le modifiche seguenti
1. Copia e incolla in App.xaml il riferimento al namespace "xmlns:ui..." nell'intestazione 
1. Copia e incolla il nodo "<ResourceDictionary>..."
1. Copia e incolla nell'intestazione della finestra il riferimento al namespace "xmlns:ui..." e ui:WindowHelper