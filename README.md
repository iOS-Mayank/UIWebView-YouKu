UIWebView-YouKu
===============

UIWebView+YouKu iOS category to simplify loading youku videos.

Instructions

1) Add these files to your project

   UIWebView+YouKu.h
   UIWebView+YouKu.m

2) Initiate UIWebView for example

   @property (strong, nonatomic) UIWebView *webView;
   @synthesize webView = _webView

   _webView = [[UIWebView alloc] initWithFrame:CGRectMake(0,0,212,172];
   //set the X,Y origin of CGRect to where you want the webView to appear.

   _webView.delegate = self;
   [_webView loadYouKuVideoID:@"XMjAzOTE4MTQ4"];
   [self.view addSubView:_webView];
