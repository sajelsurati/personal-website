<script>
    import Typewriter from 'svelte-typewriter'
    import Header from '$lib/components/Header.svelte'
    import {Card, ButtonGroup, Button} from 'flowbite-svelte'
</script>

<Header/>
<div class='justify-items-center px-20'>
    <div class = "pb-5" id='title'>
        <Typewriter interval=45>
            <h1 class='text-5xl font-bold text-center'>Sajel Surati</h1>
        </Typewriter>
    </div>
    
    
    <div class = "justify-items-center">
        <div class='flex px-20'>
            <img class = 'md:w-48' src = "picture.png" alt = "A woman smiling">
        
            <div class = "px-5" id='aboutme'>
                <h2 class='text-2xl'>About Me</h2>
                <p class='text-sm text-justify'>Hi there! My name is Sajel Surati and I am a senior at Bowdoin College studying
                mathematics and computer science. I'm interested in research at the intersection 
                of artificial intelligence and society. It is imperative to create applications
                of AI that augment human life, rather than replace aspects of what makes us human.
                I hope to explore this in graduate research in either applying ML to human-centered
                objectives, or by furthering human-aligned ML work in explainable and fair ML. In my
                free time, I run, read fantasy novels, and teach spin classes at Bowdoin! </p>
            </div>
        </div>
    
        <div id = 'projects' class='justify-items-center'>
            <p class = 'text-2xl'>Projects</p>
            <div class = 'flex space-x-3'>
                <Card size="sm">
                    <h5 class='text-lg text-bold text-center text-black'>Honors Project</h5>
                    <p class = 'text-xs text-center'>Fall 2024-Present</p>
                    <p class='text-justify'>For the entirety of my senior year, I have been working on an
                        Honors Project centered around AI for Social Good. This past semester, I have spent my time completing
                        a literature review on the current state for AI4SG, and have decided to focus on dynamic multiobjective
                        optimization (MOO). I will apply dynamic MOO to crop recommendations across multiple seasons to farmers.
                    </p>
                </Card>
                <Card size="sm" href="https://gigshare.web.app/">
                    <h5 class='text-lg text-bold text-center text-black'>Gig2Gether</h5>
                    <p class = 'text-xs text-center'>Summer 2024</p>
                    <p class='text-justify'>Gig2Gether is a web application designed by a team from Carnegie Mellon
                        to facilitate datasharing between gigworkers and policymakers. I contributed from the prototyping stage to implementation and user testing,
                        and helped edit our paper in submission to CHI 2025.
                    </p>
                </Card>
                <Card size="sm" href='https://github.com/alankct/XGBoost-From-Scratch'>
                    <h5 class='text-lg text-bold text-center text-black'>XGBoost and Poverty</h5>
                    <p class = 'text-xs text-center'>Spring 2024</p>
                    <p class='text-justify'>In Financial Machine Learning, my partner and I wanted to better understand more interpretable, powerful
                        ML methods, so we worked to engineer parts of the XGBoost algorithm from scratch. We applied our algorithm to poverty values provided by Wise Responder
                        with market return values from MCSI. Using these two datasets, we constructed a predictor using XGBoost.
                    </p>
                </Card>

            </div>
        </div>
    
        <div class = 'justify-items-center' id = 'resume'>
            <h2 class='text-2xl'>Resume/CV</h2>
        </div>
    
        <div class = 'justify-items-center' id = 'contact'>
            <h2 class='text-2xl'>Contact</h2>
            <p class='text-sm'>Email: sajelsurati@gmail.com</p>
            <ButtonGroup>
                <Button></Button>
            </ButtonGroup>
        </div>
        <p class='text-xs'>Designed by Sajel Surati in 2024 with Svelte and Tailwind CSS.</p>
    </div>
</div>

