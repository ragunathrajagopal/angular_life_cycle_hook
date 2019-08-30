# angular_life_cycle_hook
detail about angular life cycle hook

Angular:-

	1. life cycle hook
    
   specify function/property when it excetion
Constructor:-
    before execute oninit, and implement dependency injector   

1.) ngoninit:-
     once call the component after initial the function/property'
     this hook gets call only for once.

2.) ngonchange:-    
        when u pass the decorated value changes
    
3.) ngDoCheck 
       Run by Angular to detect any changes.
       Called for change detection.

4.) ngAfterContentInit
       execution ng-content after init the value 
       After ngDoCheck it is called initially.
       this hook gets call only for once.

5.) ngAfterContentChecked
        This method waits for ngContentInit to finish its execution to get started.
        Executed after all ngDocheck.
        its work by investigating the modification in the content of the component using Angular change detection apparatus
		
6.) ngAfterViewInit
    This lifecycle method gets its call after ngAfterContentChecked and finds its use only on components.
    This is very much similar to ngAfterContentInit, 
    it get invoked only after all the component view and its child view.
     it gets its call only for once.

7.) ngAfterViewChecked
    After the checking and initialization are done, this gets its called.
    After every ngAfterContentChecked method finishes its job, this method starts its
	
8.) ngOnDestroy
    This lifecycle hook gets its call after Angular destroys all the components or directives.
    This is the place where you can use your clean up logic and unsubscribe from all observable and detach from event handlers, by doing so you can prevent memory leakage.
    Gets its call just before components get removed from DOM.

	Reference link:-
		https://www.cuelogic.com/blog/angular-lifecycle
		https://codecraft.tv/courses/angular/components/lifecycle-hooks/		

QUESTIONs:-

	 Different between view and content?

	






