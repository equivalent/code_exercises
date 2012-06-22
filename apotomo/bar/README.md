Apotomo gem test

trying out functionality of Apotomo gem with rails 3.2

https://github.com/apotonick/apotomo


## conclusion

Afer playing  a while with the gem and follow allong the screencast, 
but we  decided not to use it. I see cells as a good idea for eshop but
not for application ... long story short we'll use:

        def table
          capture_haml do
            haml_tag :table, :class => "table table-striped table-bordered
              table-condensed" do
                yield if block_given?
            end
          end
        end 



        = table do
          xxx
          xxx


